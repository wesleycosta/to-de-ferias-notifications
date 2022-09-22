# # to-de-ferias-notifications
Microsserviço responsável pelo envio de notificações aos hóspedes.

[![CodeFactor](https://www.codefactor.io/repository/github/wesleycosta/to-de-ferias-notifications/badge)](https://www.codefactor.io/repository/github/wesleycosta/to-de-ferias-notifications)
[![Build status](https://wlcosta.visualstudio.com/to-de-ferias/_apis/build/status/to-de-ferias-notifications-ci)](https://wlcosta.visualstudio.com/to-de-ferias/_build/latest?definitionId=9)

## Arquitetura
Veja abaixo as interações entre os microsserviços.

<p align="center">
  <img src="https://github.com/wesleycosta/to-de-ferias-bookings/blob/main/docs/architecture.png" />
</p>

- **SPA**: Front-end em Angular;
- **API Gateway**: API gateway com Ocelot;
- **Bookings**: Microsserviço responsável pelo gerenciamento de reservas e hóspedes;
- **Rooms**: Microsserviço responsável pelo gerenciamento de quartos e categorias;
- **Notifications**: Microsserviço responsável pelo envio de notificações.
