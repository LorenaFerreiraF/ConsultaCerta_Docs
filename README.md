# 🏥 Projeto Eixo 1 - Consulta Certa

> **Sistema inteligente de agendamento e histórico médico focado em acessibilidade para idosos e inclusão digital.**

<p align="center">
  <img src="consulta_img.png" width="300">
</p>

---

## 🛠️ Tecnologias
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js,figma" />
  </a>
</p>

---

## 📝 Sobre o Projeto
O **Consulta Certa** nasceu de uma necessidade latente: eliminar as barreiras que impedem pessoas com baixa familiaridade tecnológica de gerirem sua própria saúde. Em um mundo cada vez mais digital, muitas vezes o paciente acaba excluído por interfaces complexas. Nosso sistema inverte essa lógica, oferecendo uma experiência centralizada, humana e descomplicada.

## 🎯 Objetivos
* **Agendamento Simplificado:** Fluxo intuitivo para marcação de consultas e exames com poucos cliques.
* **Prontuário Unificado:** Centralização de histórico clínico (laudos, receitas e registros) em um ambiente seguro.
* **Gestão de Absenteísmo:** Notificações em tempo real para reduzir faltas e otimizar a agenda médica.
* **Segurança (LGPD):** Proteção rigorosa de dados sensíveis de saúde, garantindo privacidade e conformidade legal.

---

## 📋 Especificação de Requisitos Funcionais (RF)

| ID | Descrição do Requisito | Eu como... | Quero/Desejo/Preciso | Para... | Responsável | Página |
|:---:|:---|:---:|:---|:---|:---:|:---:|
| **RF-01** | Permitir o cadastro de usuários do tipo 'paciente' | Paciente | Realizar meu cadastro (CRUD) (incluir, consultar/pesquisar, alterar, deletar) | Ter acessos às funcionalidades do sistema e gerenciar minhas informações pessoais | Lorena | Cadastro |
| **RF-02** | Permitir cadastro de usuários do tipo 'profissional de saúde'. | Profissional de saúde|Realizar meu cadastro – (CRUD) (incluir, consultar/pesquisar, alterar, deletar)| Divulgar meu trabalho, captar clientes e aumentar renda. | Lorena | Cadastro |
| **RF-03** |Permitir a visualização de quais serão as consultas marcadas| Paciente | Visualizar quais serão as próximas consultas que me aguardam.|Se manter informado. |  | Inicial |
| **RF-04** |Permitir a visualização de informações referentes a consulta| Paciente | Visualizar informações mais específicas sobre as consultas.|Se manter informado e se planejar para os próximos encontros com os médicos | Emily | |
| **RF-05** |Enviar notificações em rempo real sobre alterações nos agendamentos| Paciente| Ser lembrado acerca dos compromissos hospitalares sem necessariamente precisar abrir o aplicativo.|Diminuir as chances de esquecimentos dos dados das consultas e exames| Gabriel | Configurações/Api |
| **RF-06** |Exibir orientações sobre documentos necessários e preparo para exames.| Paciente| Visualizar as orientações.| Se antecipar para o caso de jejuns necessários para exames e para providenciar documentos.| | |
| **RF-07** |Permitir a confirmação de presença no atendimento.| Paciente |Confirmar minha presença a consulta.| Atualizar o status do agendamento e evitar marcação indevida de falta (absenteísmo). | Emily | Config |
| **RF-08** | Realizar cancelamento. | Paciente | Cancelar minha presença a consulta. | Informar sobre o meu não comparecimento na consulta sem precisar ir até a instituição fisicamente.| Kauan | |
| **RF-09** | Exibir histórico.| Paciente/Profissional de saúde |Acessar registros de eventos médicos e administrativos passados. |Ter uma visão completa da jornada do paciente e auxiliar na tomada de decisão clínica.| Gabriel |Página inicial/agendamento específico|
| **RF-10** | Permitir que usuários do tipo 'profissional de saúde' adicione/edite um atendimento. | Profissional de saúde |Fornecer os dados necessários para manter o paciente informado.|Abastecer a página inicial do paciente | ||
| **RF-11** | Permitir que o usuário ajuste o tamanho da fonte. | Paciente/Profissional de saúde |Facilitar a visualização das informações | Facilitar a visualização das informações.| Kauan |Todas|
| **RF-12** |Permitir o envio de documentos digitais relacionados ao atendimento. | Profissional de saúde|Realizar o upload de exames, receitas e laudos (PDF/Imagens).|Centralizar o histórico médico e facilitar a consulta durante o atendimento.| Luiz Gustavo | |
| **RF-13** | Permitir a visualização dos agendamentos na forma de uma agenda/calendário.| Paciente ou Profissional de saúde| Receber alertas imediatos sobre confirmações, cancelamentos ou atrasos.|Evitar desencontros e manter a agenda sempre atualizada para ambas as partes.| | |
| **RF-14** |Permitir que os usuários realizem busca. | Paciente/Profissional de saúde |Encontrar algum atendimento já passado. |Conferir informações não tão rescentes.|Luiz Gustavo|Todos|
---

## ⚙️ Requisitos Não Funcionais (RNF)

| ID | Descrição | Prioridade |
|:---:|:---|:---:|
| **RNF-01**|O sistema deve suportar múltiplos usuários simultâneos (exemplo: 1000 acessos). | **ALTA** |
| **RNF-02**| O sistema deve funcionar nos seguintes navegadores: Chrome, Edge e Firefox. | **Médio** |
| **RNF-03**| O sistema deve carregar em até 3 segundos.| **Médio** |
| **RNF-04**| O sistema deve Permitir ajuste de tamanho de fonte sem perda de funcionalidade ou legibilidade.| **ALTA** |
| **RNF-05**| O sistema deve garantir a proteção dos dados dos usuários, controle de acesso por perfis (paciente e profissional de saúde) e uso de protocolos de criptografia (HTTPS), assegurando a privacidade e integridade das informações. | **ALTA** |

---

## 👥 Equipe do Projeto
* **Cláudio Gabriel Araújo Chaves** 
* **Franklin Inácio Santos Guimarães** 
* **Kauan de Sousa Vilaça** 
* **Lorena Ferreira Fernandes**
* **Lucas de Paula Garcia**
* **Luiz Gustavo Fernandes Ribeiro**
* **Emily Alves Costa**
---
*Documentação gerada para a disciplina de Projeto Eixo 1 - 2026*
