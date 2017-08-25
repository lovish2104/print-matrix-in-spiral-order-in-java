import java.io.*;
class Test{
public static void spiralresult(int arr[][],int er,int ec){
	int i,sr = 0,sc = 0;
	/*  sr - starting row index
        er - ending row index
        sc - starting column index
        ec - ending column index
        i - iterator
        */
	while(sr<er && sc<ec){
		//code to traverse first row
		for(i=sc;i<ec;i++){
			System.out.print(arr[sc][i]+" ");
		}
		sr++;
		//code to traverse last column
		for(i=sr;i<er;i++){
			System.out.print(arr[i][er-1]+" ");
		}
		ec--;
		//code to traverse last row
		if(sc<ec){
		     for(i=ec-1;i>=sc;--i){
		     	System.out.print(arr[er-1][i]+" ");
		     }
		     er--; 		
		}
		//code to traverse first column
		if(sr<er){
		    for(i=er-1;i>=sr;--i){
		    	System.out.print(arr[i][sc]+" ");
     		    }
		    sc++;			
		}	
	}
  }
public static void main(String args[]){
	int er = 4;
	int ec = 4;
	int arr[][] = {{1,2,3,4},
			{5,6,7,8},
			{9,10,11,12},
			{13,14,15,16}
			};
	//this method provide spiral traversing of matrix
	spiralresult(arr,er,ec);
}
}
