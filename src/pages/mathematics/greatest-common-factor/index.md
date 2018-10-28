---
title: Greatest Common Factor
---
## Greatest Common Factor

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/mathematics/greatest-common-factor/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

Using c language calculate GCD of two numbers, let's see its syntax

```C
#include<stdio.h>
int main()
{
   int a,b,c;
   printf("Enter any two positive numbers:-\n");
   scanf("%d %d",&a,&b);
   c=gcd(a,b);
   printf("GCD of given numbers is %d",&c);
   return 0;
}
int gcd(int x,int y)
{
   if(y==0)
   return x;
   else
   return gcd(y,x%y);
}
#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->


