const modal = document.getElementById('login-modal');
const btnLogin = document.querySelector('.btn-login');
const btnComecar = document.querySelector('.btn-primary'); 

btnLogin.addEventListener('click', function() {
  modal.style.display = 'block';
});

btnComecar.addEventListener('click', function() {
  modal.style.display = 'block';
});


window.addEventListener('click', function(event) {
  if (event.target === modal) {
    modal.style.display = 'none';
  }
});
