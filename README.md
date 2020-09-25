<script src="//yihui.org/js/math-code.js"></script>
<!-- Just one possible MathJax CDN below. You may use others. -->
<script async
  src="//mathjax.rstudio.com/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# <u>QOSF Assesment </u> 

## <u>Task 2</u>

### Implement a circuit that returns $\lvert01\rangle$ and $\lvert10\rangle$ with equal probability (50% for each).

<br><br>

**Requirements :**

- [x] The circuit should consist only of CNOTs, RXs and RYs. 
- [x] Start from all parameters in parametric gates being equal to 0 or randomly chosen. 
- [x] You should find the right set of parameters using gradient descent (you can use more advanced optimization methods if you like). 
	- Used ADAM Optimizer and Gradient Descent 
- [x] Simulations must be done with sampling (i.e. a limited number of measurements per iteration) and noise. 
- [x] Compare the results for different numbers of measurements: 1, 10, 100, 1000. 
- [x] **Bonus Question**: How to make sure you produce state $\lvert01\rangle + \lvert10\rangle$ and not $\lvert01\rangle - \lvert10\rangle$ ?

 

