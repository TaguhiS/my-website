const button = document.getElementById('myButton');

button.addEventListener('click', function() {
    alert('Congratulations! The code is working');
    button.textContent = 'Success';
    button.style.transform = 'scale(0.95)';
    setTimeout(() => {
        button.style.transform = 'scale(1)';
    }, 200);
});

console.log('Website opened! GitHub Pages is working');