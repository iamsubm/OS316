#include<stdio.h>
int main()
{
	double p;
	//convert all input into one SI unit nanosecond
	int memory_acess_time=100;
	long int pge_replacement=20000000;
    long int pge_empty=8000000;
	float pge_replaced_time=0.7;
	float pge_remaining_time=1-0.7;
	int maxm_acess_time=200;
	
	//(1-p) is probalitiy of find page fault rate
//	((1-p)*memory_acess_time )+ (page_replaced_time *p *page_replacement)+ (page_remaining_time* p *page_empty)=maximum_acess_time;

int q=pge_replaced_time*pge_replacement;
int r=pge_remaining_time*pge_empty;
float s=q+r-100;
p=100/s;

	printf("\nnmost extreme satisfactory page-fault rate for get to time is  %lf",p);
	printf("\nnmost extreme satisfactory page-fault percentage for get to time is  %lf ",p*100);
	printf("%%");
}
