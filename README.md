# multidimensional-arrays
#include &lt;iostream>  using namespace std;  int main() {//||=== Build: Debug in multi array3 (compiler: GNU GCC Compiler) ===| //D:\programing\c++ tutorials\program c++\multi array3\main.cpp||In function 'int main()':| //D:\programing\c++ tutorials\program c++\multi array3\main.cpp|7|error: too many initializers for 'int [2][3][4]'| ||=== Build failed: 1 error(s), 0 warning(s) (0 minute(s), 0 second(s)) ===|    
  int johans[2][3][4]={{
  	{4,2,3,5},
  	{3,5,6,9},
  	{4,7,6,10},
  },
  {
  	{71,34,56,67},
  	{91,92,93,94},
  	{100,101,102,103}
  },
  };// the problem lies on how the rows and columns have been placed   
    //4,2,3,5     //3,5,6,9     //4,7,6,10    
     for (int i=0; i&lt;2;++i){ 
             for(int j=0;j&lt;3;++j){ 
                             for(int z=0;z&lt;4;++z){   
                                               cout&lt;&lt;"Johans ["&lt;&lt;i&lt;&lt;"]["&lt;&lt;j &lt;&lt;"]["&lt;&lt;z&lt;&lt;"]"&lt;&lt;"J= "&lt;&lt; 
                                               johans[i][j][z]&lt;&lt;endl;                 }          }     }     
                                                return 0;  }

