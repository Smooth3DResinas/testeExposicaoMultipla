# Testes de exposição de resinas

Aqui iremos explicar como realizar os testes de exposição das resinas **Smooth3D** utilizando os arquivos de pré formatados.

# Como imprimir:


Você deve navegar até a pasta relacionada ao modelo de sua impressora e copiar para o pendrive o arquivo relacionado a resina que você quer utilizar, por exemplo:

- calibracao_0.8_1.8seg.ctb
- calibracao_1.6_2.6seg.ctb

Após o arquivo ser copiado para o pendrive, deve ser realizado o processo padrão de impressão.

# Impressoras Compatíveis:

- ELEGOO MARS 2 PRO [ctb]
- QIDI Shadow5.5s [ctb]
- Anycubic Photon S [pws]

# Analisando os resultados:


## Sub Exposição:
1. Os recursos encolherão criando algum espaçamento entre os elementos.
2. Alguns elementos não serão impressos ou aparecerão falhados.
3. No geral, os elementos vão parecer mais finos que o normal.

## Sobre Exposição:
1. Os recursos se expandirão e irão se sobrepor ao elemento vizinho mais próximo.
2. Os menores recursos podem ser impressos (devido expansão e mais pixels curados).
3. No geral, parecerá gordo e largo.

## Exposição Ideal:
1. Os recursos parecem iguais em comparação com a visualização.
2. Os espaçamentos são perfeitos (sem reduzir ou expandir para o vizinho)
3. Os menores recursos estão faltando (é muito difícil curar um único pixel sem sobre exposição).
4. No geral, parece nítido e preciso.

# Exemplos:

### Espirais:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_spirals.png?raw=true)

### Barras Zebra:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_bars.png?raw=true)

### Pilares:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_pillars.png?raw=true)

### Texto:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/calibration_resinfinder_text.png?raw=true)

## Amostra:

![alt text](https://github.com/Smooth3DResinas/calibracao/blob/main/readme/exemplo.jpg?raw=true)
