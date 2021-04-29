Entrega_Proyecto_01.X
BOLAÑOS BLANCO ISMAEL 7CV7 

#include <avr/io.h>
#define F_CPU 1000000UL
#include <util/delay.h>

int main(void) {
    DDRB = 0xFF;
    while (1) {
        for(int i=0;i<5;i++){      
        if(i=0){
        PORTB = 0xff;  
        _delay_ms(5000);
        PORTB = 0x00;
        _delay_ms(5000);
        }
        if(i=1){
        PORTB = 0xff;  
        _delay_ms(3500);
        PORTB = 0x00;
        _delay_ms(3500);
        }
        if(i=2){
        PORTB = 0xff;  
        _delay_ms(1500);
        PORTB = 0x00;
        _delay_ms(1500);
        }
        if(i=3){
        PORTB = 0xff;  
        _delay_ms(1000);
        PORTB = 0x00;
        _delay_ms(1000);
        }
        if(i=4){
        PORTB = 0xff;  
        _delay_ms(500);
        PORTB = 0x00;
        _delay_ms(500);
        }

        }

        }
}
