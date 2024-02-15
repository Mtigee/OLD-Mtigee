ar data = document.querySelectorAll("[data-count]");
var values = Array.from(data).map(function (x) {
  return parseInt(x.dataset.count, 10);
});
Math.max(...values);
