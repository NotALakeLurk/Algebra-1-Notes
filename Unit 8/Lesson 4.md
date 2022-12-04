# Vocab
- `Long Division`: a method of dividing polynomials by hand
- `Synthetic Division`: a quicker method of dividing polynomials by hand; applicable when, a polynomial is being divided by a binomial in the form of $x-h$

# Notes
- $\frac{a+b}{c} = \frac{a}{c} + \frac{b}{c}$
- When dividing polynomials, make sure the degree of the divisor $\frac{}{x}$ is less that that of the dividend $\frac{x}{}$, that the degree of the remainder is less than that of the divisor, and that both polynomials are written in standard form
- `Synthetic Division` is the best division

# Long Division
1. Fill in missing terms with $0$
2. Divide the highest powers, write the quotient into answer
3. Multiply the next term of the divisor by the quotient and use to subtract from dividend as normal
4. Repeat steps $2$ - $3$ until the result of step $3$ becomes the remainder

## Example

$$
	\frac{y^3+11y^2+2}{y+3}
$$

1. <table>
	<thead>
		<td>
		<th>
		<th>
		<th>
		<th>
	<tr>
		<td>y+3|
		<td>y^3
		<td>+11y^2
		<td>+0
		<td>+2
	</table>
2. 
	- $\frac{y^3}{y}=y^2$
	- $3 \times y^2 = 3y^2$
	- <table>
		<thead>
			<td>
			<th>
			<th>y^2
			<th>
			<th>
			<th>
		<tr>
			<td>y+3|
			<td>y^3
			<td>+11y^2
			<td>+0
			<td>+2 
		</table>
3. <table>
	<thead>
		<td>
		<th>
		<th>y^2
		<th>
		<th>
		<th>
	<tr>
		<td>y+3|
		<td>y^3
		<td>+11y^2
		<td>+0
		<td>+2
	<tr>
		<td>
		<th>-y^3
		<th>-3y^2
	<tr>
		<td>
		<td>
		<td>8y^2
		<td>+0
	</table>
4. 
	- <table>
		<thead>
			<td>
			<th>
			<th>y^2
			<th>+8y
			<th>
			<th>
		<tr>
			<td>y+3|
			<td>y^3
			<td>+11y^2
			<td>+0
			<td>+2
		<tr>
			<td>
			<th>-y^3
			<th>-3y^2
		<tr>
			<td>
			<td>
			<td>8y^2
			<td>+0
		<tr>
			<td>
			<td>
			<th>-8y^2
			<th>-24y
		<tr>
			<td>
			<td>
			<td>
			<td>-24y
			<td>+2
		</table>
	- <table>
		<thead>
			<td>
			<th>
			<th>y^2
			<th>+8y
			<th>-24
			<th>
		<tr>
			<td>y+3|
			<td>y^3
			<td>+11y^2
			<td>+0
			<td>+2
		<tr>
			<td>-
			<th>y^3
			<th>+3y^2
		<tr>
			<td>
			<td>
			<td>8y^2
			<td>+0
		<tr>
			<td>
			<td>-
			<th>8y^2
			<th>+24y
		<tr>
			<td>
			<td>
			<td>
			<td>-24y
			<td>+2
		<tr>
			<td>
			<td>
			<td>-
			<th>-24
			<th>-72
		<tr>
			<td>
			<td>
			<td>
			<td>
			<td>74
			<td>R
		</table>
	- <table>
		<thead>
			<td>
			<th>
			<th>y^2
			<th>+8y
			<th>-24
			<th>R 74
		<tr>
			<td>y+3|
			<td>y^3
			<td>+11y^2
			<td>+0
			<td>+2
		<tr>
			<td>-
			<th>y^3
			<th>+3y^2
		<tr>
			<td>
			<td>
			<td>8y^2
			<td>+0
		<tr>
			<td>
			<td>-
			<th>8y^2
			<th>+24y
		<tr>
			<td>
			<td>
			<td>
			<td>-24y
			<td>+2
		<tr>
			<td>
			<td>
			<td>-
			<th>-24
			<th>-72
		<tr>
			<td>
			<td>
			<td>
			<td>
			<td>74
			<td>R
		</table>
	- $\frac{y^3+11y^2+2}{y+3} = y^2+8y-24+\frac{74}{y+3}$

# Synthetic Division
1. Write the coefficients of the dividend in standard form, filling in missing powers with $0$; change the sign of $h$ and place it to the left
2. Write the leading coefficient to the answer
3. Multiply by $h$ and write the product under the next term
4. Add to the term above and write the sum to the answer
5. Repeat steps $3$ and $4$ for each remaining term, the result of the last operation will become the remainder
6. Divide each of the polynomial's variables by $x$
7. Rejoin the coefficients and variables, adding the remainder divided by the divisor to the end

## Example
$$
	\frac{x^4-5x^3+7x+12}{x-6}
$$

1. <table>
		<thead>
			<td>6|
			<td>1
			<td>-5
			<td>+0
			<td>+7
			<td>+12
		<tr>
			<td>+|
			<th>
			<th>
			<th>
			<th>
			<th>
		<tr>
			<td>
			<td>
			<td>
			<td>
			<td>
			<td>R
	</table>
2. <table>
		<thead>
			<td>6|
			<td>1
			<td>-5
			<td>+0
			<td>+7
			<td>+12
		<tr>
			<td>+|
			<th>
			<th>
			<th>
			<th>
			<th>
		<tr>
			<td>
			<td>1
			<td>
			<td>
			<td>
			<td>R
	</table>
3. <table>
		<thead>
			<td>6|
			<td>1
			<td>-5
			<td>+0
			<td>+7
			<td>+12
		<tr>
			<td>+|
			<th>
			<th>6
			<th>
			<th>
			<th>
		<tr>
			<td>
			<td>1
			<td>
			<td>
			<td>
			<td>R
	</table>
4. <table>
		<thead>
			<td>6|
			<td>1
			<td>-5
			<td>+0
			<td>+7
			<td>+12
		<tr>
			<td>+|
			<th>
			<th>6
			<th>
			<th>
			<th>
		<tr>
			<td>
			<td>1
			<td>+1
			<td>
			<td>
			<td>R
	</table>
5. 
	- <table>
		<thead>
			<td>6|
			<td>1
			<td>-5
			<td>+0
			<td>+7
			<td>+12
		<tr>
			<td>+|
			<th>
			<th>6
			<th>+6
			<th>
			<th>
		<tr>
			<td>
			<td>1
			<td>+1
			<td>+6
			<td>
			<td>R
		</table>
	- <table>
		<thead>
			<td>6|
			<td>1
			<td>-5
			<td>+0
			<td>+7
			<td>+12
		<tr>
			<td>+|
			<th>
			<th>6
			<th>+6
			<th>+36
			<th>
		<tr>
			<td>
			<td>1
			<td>+1
			<td>+6
			<td>+43
			<td>R
		</table>
	- <table>
		<thead>
			<td>6|
			<td>1
			<td>-5
			<td>+0
			<td>+7
			<td>+12
		<tr>
			<td>+|
			<th>
			<th>6
			<th>+6
			<th>+36
			<th>+258
		<tr>
			<td>
			<td>1
			<td>+1
			<td>+6
			<td>+43
			<td>R 270
		</table>
6. $\frac{x^4+x^3+x^2+x}{x} = x^3+x^2+x$
7. $x^3+x^2+6x+43+\frac{270}{x-6}$