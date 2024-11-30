package com.jspiders.chaining;
class Hotel{
	Hotel(){
		System.out.println("KFC");
	}
	Hotel(int a){
		this();
		System.out.println("Dominos");
	}
	Hotel(String s){
		this(10);
		System.out.println("McDonalds");
	}
}

public class java{
	public static void main(String[] args) {
		Hotel h1=new Hotel("ABC");
}
}
