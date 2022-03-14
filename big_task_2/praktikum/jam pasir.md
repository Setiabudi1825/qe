package com.company;
public class Main
{
    public static void main(String [] args){

        int n=5;
        for (int i=0; i<=n-1; i++){

            for (int j=0;j<=i;j++){

                System.out.print(" ");
            }
            for (int k=0; k>=(i-n+1);k--){
                System.out.print("*");
            }
            for (int l=i;l<n-1;l++){
                System.out.print("*");
            }System.out.print("\n");
            }

        for (int i=0; i<n;i++){
            for (int j=0;j<n-i;j++){
                System.out.print(" ");

            }
            for (int j=0;j<(i+1);j++){
                System.out.print("*");
            }
            for (int l=0;l<i;l++) {
                System.out.print("*");
            }System.out.print("\n");
        }
    }
}