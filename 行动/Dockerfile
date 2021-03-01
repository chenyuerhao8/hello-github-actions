＃include  "stm32f10x.h"
#include "stm32f10x.h"
#include"delay.h"
#include"led.h"

int main(void)
{
	delay_init();
	LED_Init();
	
	
	while(1)
	{
	GPIO_ResetBits(GPIOB,GPIO_Pin_5);
	delay_ms(500);
	GPIO_SetBits(GPIOB,GPIO_Pin_5);	
  delay_ms(500);
	
	GPIO_ResetBits(GPIOB,GPIO_Pin_1);
	delay_ms(500);	
	GPIO_SetBits(GPIOB,GPIO_Pin_1);
	delay_ms(500);
	
	GPIO_ResetBits(GPIOB,GPIO_Pin_0);
	delay_ms(500);	
	GPIO_SetBits(GPIOB,GPIO_Pin_0);
	delay_ms(500);
	
	
	
}

}
