// getting the html elements
const MinusBtn = document.getElementById("MinusBtn");
const AddBtn = document.getElementById("AddBtn");
const resetBtn = document.getElementById("resetBtn");
const displayValue = document.getElementById("displayValue");

// for Minus button click
MinusBtn.addEventListener("click", () => {
  const value = Number(displayValue.innerText);
  if (value > -11) {
    displayValue.innerText = value - 1;
  } else {
    alert("-10 values are not allowed");
  }
});

// for Add button click
AddBtn.addEventListener("click", () => {
  const value = Number(displayValue.innerText);
  if (value >= 20) {
    alert("20+ values are not allowed");
  } else {
    displayValue.innerText = value + 1;
  }
});

// for reset button click
resetBtn.addEventListener("click", () => {
  displayValue.innerText = 0;
});