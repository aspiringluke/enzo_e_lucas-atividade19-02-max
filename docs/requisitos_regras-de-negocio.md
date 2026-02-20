# Requisitos Funcionais

### RF01 – Login
- O usuário deve logar no sistema com login OU número de telefone e senha.

### RF02 – Agendar banho e tosa
- O usuário deve poder agendar um dia para banho e tosa.

### RF03 - Mostrar agendamentos
- O usuário pode ver quais dias estão ocupados e o quão ocupado cada dia está.

### RF04 - Cancelar
- O usuário pode cancelar um agendamento anteriormente marcado.

### RF05 - Reagendar
- O usuário pode reagendar um banho ou tosa anteriormente agendado.

# Requisitos Não Funcionais 

### RNF01 - Criptografia
- Nenhuma informação sensível (como, por exemplo, as credenciais de Login do usuário) pode ser armazenada sem criptografia.

### RNF02 - Evitar congestionamento
- Os servidores devem ter lógica que evita redundância de tráfego de rede para impedir sobrecarga dos servidores.

# Regras de negócio

### RN01 - Máximo de 10 pets por dia
- A empresa não se dispõe a tosar e/ou banhar mais de 10 pets diariamente.

### RN02 - Confirmação do agendamento via pagamento
- O serviço só será disponibilizado uma vez que o pagamento tenha sido confirmado.
