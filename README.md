# ping-pong
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author Velizar
 */
public class PingPong {
    public static void main (String [] args){
        
      for(int num = 0; num < 100;num++){
         if(num % 15 == 0){
              System.out.println(num +" " + "ping-pong");
             
             
        }
         else if(num % 5 == 0){
              System.out.println(num +" " + "pong");
             
      }
       else  if(num % 3 == 0){
              System.out.println(num + " " +"ping");
             
             
        } 
      }
    }
}

