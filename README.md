# dataTypes
Learning About Data Types
package com.JohnHay;

public class Main {

    public static void main(String[] args) {

        // Interger has a width of 32
        
        int myMinValue = - 2_147_483_648;
        int myMaxValue =   2_147_483_647;
        int myTotal = (myMinValue/2);
        System.out.println("myTotal = " + myTotal);

        // byte has a width of 8
        
        byte myByteMinValue = -128;
        byte myByteMaxValue = 127;
        byte myNewByteValue = (byte) (myByteMaxValue/2);  //casting treat as byte
        System.out.println("myNewByteValue = " + myNewByteValue);


        // short has a width of 16
        
        short myShortMinValue = -32767;
        short myShortMaxValue =  32767;
        short myNewShortValue = (short) (myShortMaxValue/2); 
        
        //Need to cast again by default generally speaking int isway to go as Java converts to integer.

        // long has a width of 64
        long myLongValue = 9_223_372_036_854_775_807L;


	// write your code here
    }
}
