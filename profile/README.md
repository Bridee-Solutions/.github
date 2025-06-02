<img src="https://i.ibb.co/KxRRhC0f/bridee.png" alt="Logo bridee" style="width: 800px; display: block; margin: 0 auto 20px auto;" />

bridee. é uma plataforma desenvolvida como Trabalho de Conclusão de Curso (TCC) de Análise e Desenvolvimento de Sistemas, com o objetivo de facilitar a conexão entre **noivas** e **assessoras de casamento**, automatizando processos e oferecendo ferramentas práticas para a organização de casamentos.

O desenvolvimento foi dividido em dois ciclos:

- 📱 **Aplicativo Mobile** – desenvolvido no 4º semestre
- 💻 **Aplicação Web** – desenvolvida no 3º semestre

Este projeto foi realizado na disciplina de **Projeto e Inovação** na [SPTech School (antiga Bandtec)](https://www.sptech.school/), com duração total de um ano (2024/02 - 2025/01).

---
## 🎯 Objetivo do Projeto

A bridee. busca resolver problemas enfrentados por noivas e assessoras, como:

- Falta de centralização das informações do casamento
- Processos manuais e retrabalho
- Comunicação desorganizada com fornecedores
- Dificuldade para manter controle financeiro 

## 💻 Funcionalidades da Aplicação Web (3º semestre)

Voltada para **casais** e **assessoras de casamento**, a versão web oferece um conjunto robusto de ferramentas de organização:

### Para casais:
- **Lista de tarefas** para organizar preparativos
- **Lista de convidados** com integração ao WhatsApp
- **Calculadora financeira** com geração de arquivo `.csv` com os gastos
- **Home** com visão geral do casamento, incluindo fornecedores e assessor escolhido
- **Solicitação de assessor**: ao escolher um assessor, o pedido é enviado e, caso aceito, o compromisso entra automaticamente no calendário do profissional

### Para assessores:
- **Calendário integrado** com os eventos confirmados
- **Gestão de solicitações**: visualização de casais que solicitaram atendimento e opção de aceitar ou recusar

---

## 📱 Funcionalidades do Aplicativo Mobile (4º semestre)

O aplicativo tem foco exclusivo no **casal**, com uma experiência mais visual e simplificada:

- **Lista de tarefas**
- **Home personalizada** com visão geral do casamento
- **Calculadora financeira**
- **Configurações do usuário**
- **Telas de inspiração** com imagens para o casal favoritar (ex: vestidos, decoração etc.)
- **Explorar fornecedores**:
  - Filtro por **categoria** (ex: decoração, florista, local para casar, gastronomia etc.)
  - Filtro por **estilo de casamento** (ex: praia, ao ar livre, castelo...)

---


## 🧩 Estrutura do Projeto

O projeto está dividido em múltiplos repositórios, cada um com responsabilidades específicas:

| Repositório | Linguagem | Descrição |
|------------|-----------|--------------|
| `bridee.auth.server` | Kotlin | Serviço de autenticação e autorização |
| `bridee.app` | Kotlin | Aplicativo mobile (Android) |
| `bridee.api` | Java | API backend da aplicação |
| `bridee.ui` | JavaScript | Interface web para gestão |
| `bridee.bucket.lambda` | Java | Funções Lambda para upload e manipulação de arquivos |
| `bridee.aws.infra` | HCL | Infraestrutura em AWS via Terraform |
| `bridee.api.gateway` | Dockerfile |  Orquestração de serviços com API Gateway |
| `bridee.pipeline-CI-CD` | Dockerfile |  Pipelines de CI/CD |
| `bridee.wedding.job` | Java |  Jobs automáticos para notificações e agendamentos |
| `bridee.bucket.function` | Java | Funções auxiliares para armazenamento |
| `bridee.azure.infra` | HCL |  Infraestrutura em Azure via Terraform |

---

## 🛠️ Tecnologias Utilizadas

- **Frontend Web**: React
- **Mobile**: Kotlin Jetpack Compose
- **Backend**: Java + Spring Boot | Kotlin Jetpack Compose
- **Infraestrutura**: AWS, Azure, Terraform
- **CI/CD**: Docker + Pipelines
- **Integrações**: 

---

## 📚 Licença
Este projeto é de caráter educacional e não possui fins comerciais.
Cada módulo possui seu próprio README com instruções específicas. 


