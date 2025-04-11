document.getElementById('login-form')?.addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Connexion réussie !');
    window.location.href = 'produits.html';
});
