# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212224040219
# Developed By:Nikhil H
# 1-Norm of a Matrix

		import os
		os.environ["OPENBLAS_NUM_THREADS"] = "1"
		
		import numpy as np
		
		# Input matrix
		A = np.array(eval(input()))
		
		# Find 1-Norm (maximum column sum)
		norm1 = np.linalg.norm(A, 1)
		
		# Display result with 2 decimal places
		print(f"{norm1:.2f}")


# 2-Norm of a Matrix

		import os
		os.environ["OPENBLAS_NUM_THREADS"] = "1"
		
		import numpy as np
		
		# Input matrix
		A = np.array(eval(input()), dtype=float)
		
		# Find L2-Norm (Spectral norm)
		norm2 = np.linalg.norm(A, 2)
		
		# Display result with 2 decimal places
		print(f"{norm2:.2f}")

# Infinity Norm of a Matrix

	import os
	os.environ["OPENBLAS_NUM_THREADS"] = "1"
	
	import numpy as np
	
	# Input matrix
	A = np.array(eval(input()), dtype=float)
	
	# Find Infinity Norm (maximum row sum)
	inf_norm = np.linalg.norm(A, np.inf)
	
	# Display result with 2 decimal places
	print(f"{inf_norm:.2f}")


```
## Output:
### 1-Norm of a Matrix
<img width="1304" height="196" alt="image" src="https://github.com/user-attachments/assets/9967758b-1bd7-43ad-9ec6-92ef8865ddfb" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1280" height="218" alt="image" src="https://github.com/user-attachments/assets/7aa4decc-4560-4cf0-88fb-d304b49c7e15" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1275" height="174" alt="image" src="https://github.com/user-attachments/assets/a066375b-660c-4224-8fa5-2af434a0215a" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
