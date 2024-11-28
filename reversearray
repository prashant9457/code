#include<stdio.h>
int main() {
	int n;
	printf("enter the size of array");
	scanf("%d" ,&n);
	int arr[n];
	for (int i=0; i<n; i++) {
  		printf("nenter the element number %d", i+1);
  		scanf("%d", &arr[i]);
}
	for (int i = 0; i < n / 2; i++) {
        // Swap the elements
        int temp = arr[i];
        arr[i] = arr[n - i - 1];
        arr[n - i - 1] = temp;
    }
    printf("reversed array is\n");
  	for (int i=0; i<n; i++) {
  		printf("%d ", arr[i]);
	}
	return 0;
}
