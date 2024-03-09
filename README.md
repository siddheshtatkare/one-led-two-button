
# one-led-two-button
#Embedded_Softwar_Enginner 


  #include <reg51.h>
	 
	 sbit LED1=P1^0;
	 sbit Switch1=P2^6;
	 sbit Switch2=P2^7;
	 
	 void main(){
		 LED1=1;
		 
		while(1){
		
		if(Switch1==0){
		LED1=0;
		}
		if(Switch2==0){
			LED1=1;
		}
		
		
		}
}
			

 


