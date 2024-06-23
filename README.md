# Exercício Básico de Redes com 1 Switch e 4 Computadores

## Descrição

Este repositório contém um exercício básico de redes, cujo objetivo é configurar uma rede simples utilizando um switch e quatro computadores. O exercício é destinado a iniciantes em redes de computadores, proporcionando uma introdução prática aos conceitos de rede local (LAN) e à configuração básica de dispositivos de rede.

## Objetivos

- Compreender os conceitos básicos de redes de computadores.
- Aprender a configurar uma rede local utilizando um switch.
- Praticar a configuração de endereços IP estáticos em computadores.
- Testar a conectividade entre os dispositivos da rede.

## Componentes da Rede

1. **Switch:** Um dispositivo de rede que conecta os computadores, permitindo a comunicação entre eles.
2. **Computadores:** Quatro computadores que serão configurados para se comunicar através do switch.

## Requisitos

- Um switch (real ou emulador de rede, como Cisco Packet Tracer).
- Quatro computadores (ou máquinas virtuais).
- Cabos Ethernet para conectar os computadores ao switch (caso esteja usando hardware real).
- Software para configuração de rede (opcional, dependendo do sistema operacional utilizado).

## Passos para Configuração

### 1. Conexão Física

1. Conecte cada um dos quatro computadores a uma porta do switch utilizando cabos Ethernet.

### 2. Configuração de Endereços IP

Em cada computador, configure um endereço IP estático. Abaixo está um exemplo de configuração:

- **Computador 1:**

   - IP: 192.168.10.1
  - Máscara de Sub-rede: 255.255.255.0
  
  
- **Computador 2:**
  
  - IP: 192.168.10.2
  - Máscara de Sub-rede: 255.255.255.0
  

- **Computador 3:**

  - IP: 192.168.10.3
  - Máscara de Sub-rede: 255.255.255.0
  

- **Computador 4:**
  
  - IP: 192.168.10.4
  - Máscara de Sub-rede: 255.255.255.0
  

### 3. Teste de Conectividade

1. Abra o terminal ou prompt de comando em cada computador.
2. Utilize o comando `ping` para testar a conectividade entre os computadores. Por exemplo, no Computador 1, execute:

   ```sh
   ping 192.168.10.2
   ping 192.168.10.3
   ping 192.168.10.4
   ```

   Repita o processo nos outros computadores, alterando os endereços IP conforme necessário.

## Resultados Esperados

- Todos os computadores devem conseguir se comunicar entre si.
- Os comandos `ping` devem retornar respostas bem-sucedidas, indicando que os pacotes estão sendo enviados e recebidos corretamente.

## Conclusão

Este exercício básico demonstra como configurar e testar uma rede local simples usando um switch e quatro computadores. A compreensão desses conceitos básicos é fundamental para avançar em estudos mais complexos de redes de computadores.

## Autor

- Samir Santos (https://github.com/SamSantos81)

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações ou dúvidas, entre em contato:

- Email: samdevsecops@outlook.com
- GitHub: SamSantos81 

---

Aproveite o exercício e bons estudos sobre redes de computadores!
