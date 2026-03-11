# 🚨 Emergência Transital

> **Sua segurança em um toque.**  
> O Emergência Transital é uma ferramenta focada em salvar vidas, conectando usuários a serviços de resgate e contatos de confiança de forma instantânea.

---

## 📖 Como utilizar o aplicativo

Desenvolvemos uma interface **minimalista** para que o uso seja intuitivo, mesmo em situações de alto estresse.

### 1. Configuração Inicial (Primeiro Acesso)
Para que o socorro seja eficaz, o usuário deve:
*   **Permitir Localização:** Essencial para que o resgate encontre o local exato.
*   **Cadastrar Contatos SOS:** Defina até 3 pessoas que receberão um SMS automático.
*   **Ficha Médica:** Insira tipo sanguíneo e alergias básicas para agilizar o atendimento médico.

### 2. Fluxo de Emergência (Uso Real)
1.  **Acionamento:** Na tela principal, pressione o botão de socorro por **2 segundos**.
2.  **Envio Automático:** O app envia sua localização para a central e dispara alertas para seus contatos SOS.
3.  **Monitoramento:** A tela exibirá o tempo estimado de chegada (ETA) da unidade de resgate.
4.  **Instruções:** Siga as dicas de segurança exibidas no card (ex: "Afaste-se da pista").

---

## 💻 Códigos de Interface (UI Copy)

Se você estiver implementando as telas, utilize estas chaves de texto para manter o padrão minimalista:

```json
{
  "header_title": "Emergência Transital",
  "welcome_msg": "Pronto para sua segurança. ✨",
  
  "action_main": "PRESSIONE PARA SOCORRO",
  "action_sub": "Segure por 2s para confirmar",
  
  "status_rescue": "Ajuda a caminho. Chegada em: {min} min.",
  "status_family": "Família e contatos SOS já foram avisados.",
  
  "tip_safety": "Dica: Mantenha-se visível, mas fora do fluxo de veículos.",
  "permission_req": "Precisamos da sua localização para o resgate te encontrar."
}

