// Menu vertical
var menuItems = document.querySelectorAll('.menu-item');

menuItems.forEach(function(menuItem) {
	menuItem.addEventListener('click', function() {
		menuItem.classList.toggle('active');
	});
});

// Imagen horizontal
var images = document.querySelectorAll('.image');

images.forEach(function(image) {
	image.addEventListener('click', function() {
		image.classList.toggle('active');
	});
});
