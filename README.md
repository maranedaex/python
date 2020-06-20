# python
python Jupyter notebook

### Convoluciones 2D en Python (OpenCV 2, numpy)

Para demostrar el filtrado 2D basado en el núcleo.

```python
image = cv2.imread ('lena512.bmp', cv2.IMREAD_GRAYSCALE) .astype (float) / 255.0

kernel = np.array ([[1, 1, 1],
                    [0, 0, 0],
                    [-1, -1, -1]])

filter = cv2.filter2D (src = imagen, kernel = kernel, ddepth = -1)
cv2.imshow ('bordes horizontales', filtrados)
```

Además, `concol-cv2-manual.ipynb` implementa una convolución 2D manual.
