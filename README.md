# 🛩️ ZeepFly ACARS Client

## 📋 Sobre o Sistema

O **ZeepFly ACARS Client** é um aplicativo desktop desenvolvido para pilotos de simuladores de voo que desejam integrar suas sessões de voo com sistemas ZeepFly para companhias aéreas virtuais (VA - Virtual Airlines). O sistema oferece uma experiência completa de ACARS (Aircraft Communications Addressing and Reporting System) diretamente integrado ao Microsoft Flight Simulator.

## ✈️ Funcionalidades Principais

### 🎯 **Plano de Voo**
- **Integração com ZeepFly Pilot System**: Importação automática de planos de voo ativo
- **Tracking em Tempo Real**: Monitoramento de posição, altitude, velocidade e status dos motores
- **Detecção Automática**: Início e fim de voo detectados automaticamente
- **Status de Voo**: Controle de status (agendado, em progresso, concluído)

### 🌤️ **Informações Meteorológicas**
- **METAR em Tempo Real**: Dados meteorológicos atualizados
- **Múltiplos Aeroportos**: Consulta de condições em diferentes aeroportos
- **Interface Intuitiva**: Visualização clara das condições meteorológicas

### 📊 **Logbook**
- **Histórico Completo**: Registro de todos os voos realizados
- **Estatísticas Detalhadas**: Tempo de voo, distância, aeronaves utilizadas
- **Exportação**: Possibilidade de exportar dados para análise

### ⚙️ **Configurações**
- **Personalização**: Configurações de interface e comportamento
- **Preferências de Usuário**: Salvar configurações personalizadas

## 🖥️ Requisitos do Sistema

### **Sistema Operacional**
- **Windows**: Windows 10/11 (64-bit)

### **Simulador**
- **Microsoft Flight Simulator 2020** (versão 1.24.2 ou superior)

### **Hardware Mínimo**
- **Processador**: Intel i5 ou AMD equivalente
- **Memória**: 8GB RAM
- **Armazenamento**: 250MB de espaço livre
- **Rede**: Conexão com internet para sincronização

## 📦 Download e Instalação

### **Windows**
1. Baixe o arquivo `ZeepFly-ACARS-Setup.exe` da seção de releases
2. Execute o instalador como administrador
3. Siga as instruções do assistente de instalação
4. O aplicativo será instalado automaticamente

### **Versão Portable (Windows)**
- Baixe o arquivo `ZeepFly-ACARS-Portable.exe`
- Execute diretamente sem instalação
- Ideal para uso em múltiplas máquinas

## 🚀 Primeiro Uso

### **1. Configuração Inicial**
- Execute o aplicativo pela primeira vez
- Faça login com suas credenciais da companhia aérea virtual
- Configure as preferências básicas

### **2. Integração com MSFS**
- Certifique-se de que o Microsoft Flight Simulator está em execução
- O ACARS se conectará automaticamente via SimConnect
- Verifique se a conexão está ativa na interface

### **3. Primeiro Voo**
- Importe um plano de voo do SimBrief no ZeepFly Pilot System ou crie manualmente (Para voo de Helicóptero)
- Inicie o voo no simulador
- O sistema detectará automaticamente o início do voo
- Acompanhe o progresso em tempo real

## 🐛 Solução de Problemas

### **Problema**: Aplicativo não inicia
**Solução**:
- Verifique se o .NET Framework está instalado (Windows)
- Execute como administrador
- Verifique os logs em `%APPDATA%/ZeepFly-ACARS/logs/`

### **Problema**: Não conecta com o MSFS
**Solução**:
- Certifique-se de que o MSFS está em execução
- Verifique se o SimConnect está ativo
- Reinicie o aplicativo
- Verifique as configurações de firewall

### **Problema**: Dados não sincronizam
**Solução**:
- Verifique a conexão com a internet
- Confirme se as credenciais estão corretas
- Verifique se a API está acessível
- Tente fazer logout e login novamente

## 📞 Suporte

### **Canais de Suporte**
- **GitHub Issues**: [Repositório Principal](https://github.com/zeepfly/zeep-fly-acars)
- **Discord**: [Servidor da comunidade AeroNav Sim](https://discord.gg/T8mFfs9FFy)
- **Email**: support@zeepfly.com

### **Documentação**
- **Manual do Usuário**: Disponível na documentação oficial
- **Tutoriais**: [Vídeos e guias no canal oficial](https://www.youtube.com/@AeroNavSim)

## 🔄 Atualizações

### **Atualizações Automáticas**
- O aplicativo verifica atualizações automaticamente
- Notificações de novas versões
- Download e instalação automática (configurável)

### **Versões Suportadas**
- **Versão Atual**: 1.0.0
- **Versão Mínima**: 0.9.0
- **Suporte**: Tempo indeterminado

## 📄 Licença

Este software é distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📈 Roadmap

### **Próximas Funcionalidades**
- [ ] **Radar em Tempo Real**: Visualização de outros voos
- [ ] **Notificações Push**: Alertas e notificações
- [ ] **Integração com Discord**: Compartilhamento de voos
- [ ] **Relatórios Avançados**: Análises detalhadas de performance
- [ ] **Suporte a Múltiplos Simuladores**: Prepar3D, X-Plane

### **Melhorias Planejadas**
- [ ] **Interface Dark/Light**: Temas personalizáveis
- [ ] **Plugins**: Sistema de plugins para extensibilidade

---

## 🏢 Sobre a ZeepFly

A **ZeepFly** é uma empresa especializada em soluções para simuladores de voo, focada em criar sistemas que aproximam a experiência virtual da realidade da aviação comercial.

### **Nossa Missão**
Proporcionar aos pilotos virtuais ferramentas profissionais que elevem a experiência de simulação de voo, conectando comunidades e facilitando a gestão de companhias aéreas virtuais.

### **Contato**
- **Website**: [zeepfly.com](https://zeepfly.com)
- **Email**: contactus@zeepfly.com
- **Discord**: [Comunidade AeroNav Sim](https://discord.gg/T8mFfs9FFy)

---

*Desenvolvido com ❤️ pela equipe ZeepFly*
