#include <stdio.h>
int main() {
int temp;
printf("enter the size of array");
scanf("%d" ,&temp);
int arr[temp];
for (int i=0; i<temp; i++) {
  printf("enter the element number %d", i+1);
  scanf("%d", &arr[i]);
}
for (int i = 0; i < temp - 1; i++) {
        for (int j = 0; j < temp - i - 1; j++) {
            if (arr[j] > arr[j + 1]) {
                // Swap the elements
                int temp = arr[j];
                arr[j] = arr[j + 1];
                arr[j + 1] = temp;
            }
        }
    }
  printf("sorted array is\n");
  for (int i=0; i<temp; i++) {
  printf("%d ", arr[i]);
}
    return 0;
  }
