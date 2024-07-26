# Example.STM32-EXTERNAL-FLASH-READ-by-address
STM32H747I-DISCO 보드의 qspi를 통해 external flash에 있는 데이터를 읽습니다. 

BSP 라이브러리를 이용하며, BSP_QSPI_Read 함수를 이용하여 데이터를 읽는 것이 아닌, 일반 변수 사용하듯이 데이터를 읽습니다.
```
ex)
uint8_t *flash_memory = (uint8_t *)(0x90000000);	// Address of External FLASH
```

## 사용법
1. STM32CubeProgrammer 설치
2. Hello World.bin 파일을 STM32에 업로드
