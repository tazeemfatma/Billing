import java.io.*;
import java.lang.*;
import java.util.*;
class bill1
{
    public static void main(String args[])throws Exception
    {
        
        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        float d,sum=0,g,sum1=0;
        int n,i;
        //List<Pair> prodcost=new ArrayList<Pairs>();
        System.out.println("enter the number of products");
        n=Integer.parseInt(br.readLine());
        float cost[]=new float[n];
        String prod[]=new String[n];
        float num[]=new float[n];
        float mult[]=new float[n];
        float discount[]=new float[n];
        float disper[]=new float[n];
        float gst[]=new float[n];
        for(i=0;i<n;i++)
        {
            System.out.println("enter the product name");
          prod[i]=br.readLine();
          System.out.println("enter no. of product");
          num[i]=Float.parseFloat(br.readLine());
          System.out.println("enter the cost");
          cost[i]=Float.parseFloat(br.readLine());
          System.out.println("enter discount percentage");
          discount[i]=Float.parseFloat(br.readLine());
          System.out.println("enter gst");
          gst[i]=Float.parseFloat(br.readLine());
          

        } 
        for(i=0;i<n;i++)
        {
            
          d=(discount[i]/100 )*cost[i]; 
          disper[i]=cost[i]-d; 
          mult[i]=disper[i]*num[i];
          
           sum=sum+mult[i];
           g=(gst[i]/100)*mult[i];
          
           sum1+=mult[i]+g;
          
        } 
        
         System.out.println("product list");
         System.out.println("serial no"+"\t"+"name"+"\t" +"cost"+"\t"+"no. of item"+"\t"+"discount %"+"\t"+"net cost"+"\t"+"GST");
             for(i=0;i<n;i++)
              {
              System.out.println("product"+(i+1)+"\t"+prod[i]+"\t" +cost[i]+"\t"+"\t"+num[i]+"\t"+discount[i]+"\t"+"\t"+mult[i]+"\t"+"\t"+gst[i]);
              }
           System.out.println();  
   
        System.out.println("total cost="+sum);
        System.out.println("after tax the amount is"+sum1);
        }
    }
        
