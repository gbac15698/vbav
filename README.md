# vbav#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()
{
	float a, b, c, d;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
	else if (b) printf("Mot nghiem x=%4.2f", -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
	else if (b) printf("Mot nghiem x=%4.2f", -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}
