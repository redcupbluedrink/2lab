#include <stdio.h>
#include <math.h>


/* 1
int main() {

	int a, b, c, d, e, f;
	printf("a = ");
	scanf("%d", &a);
	printf("b = ");
	scanf("%d", &b);
	printf("c = ");
	scanf("%d", &c);
	printf("d = ");
	scanf("%d", &d);
	printf("e = ");
	scanf("%d", &e);
	printf("f = ");
	scanf("%d", &f);
	int proiz = (a*b*c*d*e*f);
	int sloj = (a+b+c+d+e+f);


	if (sloj > proiz) {
		printf("Bolshe na %d", sloj - proiz);
	} else {
		printf("Menshe na %d", proiz - sloj);
	}


}
*/


/* 2
int main() {

	int a, b, c, d, e;
	printf("a = ");
	scanf("%d", &a);
	printf("b = ");
	scanf("%d", &b);
	printf("c = ");
	scanf("%d", &c);
	printf("d = ");
	scanf("%d", &d);
	printf("e = ");
	scanf("%d", &e);
	int sum = 0;


	if (a > 0) {
		sum += a;
	}
	if (b > 0) {
		sum += b;
	}
	if (c > 0) {
		sum += c;
	}
	if (d > 0) {
		sum += d;
	}
	if (e > 0) {
		sum += e;
	}
	printf("%d", sum);
}
*/


/* 3
int main() {

	int a, b, c, d;
	printf("a = ");
	scanf("%d", &a);
	printf("b = ");
	scanf("%d", &b);
	printf("c = ");
	scanf("%d", &c);
	printf("d = ");
	scanf("%d", &d);

	if (a < 0) {
		a = 0;
	}
	printf("a = %d\n", a);
	if (b < 0) {
		b = 0;
	}
	printf("b = %d\n", b);
	if (c < 0) {
		c = 0;
	}
	printf("c = %d\n", c);
	if (d < 0) {
		d = 0;
	}
	printf("d = %d\n", d);
	
}
*/


/* 4
int main() {

	int a, b, c, d, e, f, j, h;
	printf("a = ");
	scanf("%d", &a);
	printf("b = ");
	scanf("%d", &b);
	printf("c = ");
	scanf("%d", &c);
	printf("d = ");
	scanf("%d", &d);
	printf("e = ");
	scanf("%d", &e);
	printf("f = ");
	scanf("%d", &f);
	printf("j = ");
	scanf("%d", &j);
	printf("h = ");
	scanf("%d", &h);
	int pol = 0;
	int otr = 0;


	if (a > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	if (b > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	if (c > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	if (d > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	if (e > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	if (f > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	if (j > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	if (h > 0) {
		pol += 1;
	}
	else {
		otr += 1;
	}
	printf("polojitelnih: %d\n", pol);
	printf("otricatelnih: %d\n", otr);
	
}
*/ 


/* 5
int main() {

	int k = 10000;
	int a[4];
	int i;
	int n = 0;
	
	for (i = 1; i<5; i++) {
    	printf("a[%d] = ", i);
    	scanf("%d", &a[i]);
	}
	for (i = 1; i < 5; i++) {
		if (a[i]< k){
			k = a[i];
			n = i;
		}
	}
	printf("%d", n);
}
*/


/* 6
int main() {  

	int min = 100;
	int max = 0;
	int a[4];
	int i;
	
	for (i = 0; i<4; i++) {
    	printf("a[%d] = ", i);
    	scanf("%d", &a[i]);
	}
	for (i = 0; i < 4; i++) {
		if (min > a[i]) {
			min = a[i];
		}
		if (max < a[i]) {
			max = a[i];
		}
	} 
    printf("max-min = %d\n", max - min);
}
*/ 

/* 7
int main() { 

	int K, M, N, min, max;
	min=10000;
	max=-10000;
	printf("K=");
	scanf("%d", &K);
	printf("M=");
	scanf("%d", &M);
	printf("N=");
	scanf("%d", &N);
	if (min > K) {
		min = K;
	}
	if (min > M) {
		min = M;
	}
	if (min > N) {
		min = N;
	}
	if (max < K) {
		max = K;
	}
	if (max < M) {
		max = M;
	}
	if (max < N) {
		max = N;
	}
	M = (K + N + M) - (min + max);
	N = max;
	K = min;
	printf("%d %d %d",K, M, N);
}
*/


/* 8
int main() {

    int a[4];
	int i;
	int max1 = 0;
	int max2 = 0;
	
	for (i = 0; i<4; i++) {
    	printf("a[%d] = ", i);
    	scanf("%d", &a[i]);
	}
	for (i = 0; i < 4; i++) {
		if (a[i] > max1) {
			max1 = max2;
			max2 = a[i];
		}			
	}
    printf("%d %d", max1, max2);
}
*/

/* 9
int main() { 

	int a1, a2, a3, min, max;
	min = 10000;
	max = -10000;
	printf("a1 =");
	scanf("%d", &a1);
	printf("a2 =");
	scanf("%d", &a2);
	printf("a3 =");
	scanf("%d", &a3);
	if (min>a1) {
		min=a1;
	}
	if (min>a2) {
	min=a2;
	}
	if (min>a3) {
	min=a3;
	}
	if (max<a1) {
	max=a1;
	}
	if (max<a2) {
	max=a2;
	}
	if (max<a3) {
	max=a3;
	}

	if (max==a1) {
		if (min==a2) 
			printf("%d %d %d", a2, a1, a3);
		if (min==a3) 
			printf("%d %d %d", a3, a2, a1);	
	}
	if (max==a2) {
		if (min==a1) 
			printf("%d %d %d", a2, a1, a3);
		if (min==a3) 
			printf("%d %d %d", a1, a3, a2);
	}
	if (max==a3) {
		if (min==a1) 
			printf("%d %d %d", a3, a2, a1);
		if (min==a2) 
			printf("%d %d %d", a1, a3, a2);
	}
}		
*/
