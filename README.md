# ClearKM

Gestão de frotas para empresas que precisam controlar veículos, motoristas e a operação do dia a dia em um só lugar.

**Em produção:** (https://clearkm.com.br)

## Sobre

O ClearKM é uma plataforma SaaS. O motorista registra quilometragem e abastecimento pelo celular. O administrador acompanha a frota, os alertas e os relatórios no painel da empresa.

Cada empresa tem o próprio ambiente. Os dados de uma não aparecem para outra.

| Ambiente | Endereço |
| --- | --- |
| Site, planos e cadastro | (https://clearkm.com.br) |
| Painel da empresa e app do motorista | (https://app.clearkm.com.br) |
| Administração da plataforma | (https://admin.clearkm.com.br) |

## Funcionalidades

- Veículos e documentação (CRLV)
- Motoristas e CNH
- Frota em operação, aguardando ou disponível
- Jornada de quilometragem, com histórico
- Abastecimentos com comprovante
- Autonomia e consumo por veículo
- Repasse de veículo entre motoristas
- Alertas e relatórios
- Dashboard administrativo
- Usuários e permissões
- Empresas e filiais, com troca de empresa para quem tem acesso
- App do motorista instalável no celular (PWA), com uso offline

## Tecnologias

**Interface**

- React e TypeScript
- Vite e Tailwind CSS

**API**

- Python e FastAPI
- PostgreSQL

**Publicação**

- Docker
- GitHub Actions

## Acesso

- **Super Admin** — gestão da plataforma
- **Administrador** — operação da empresa
- **Motorista** — jornada, abastecimento e alertas no celular

## Segurança

Autenticação e permissões por perfil. Cada usuário acessa somente o ambiente e as funções permitidos para ele.

## Objetivo

Centralizar a gestão da frota e reduzir o controle manual de veículos, motoristas e da operação diária.

## Autor

Gabriel Reis / 
Juliano Ballestrin

Projeto em produção e também parte da minha evolução em desenvolvimento de software.

## Links

- Site: (https://clearkm.com.br)
- Aplicação: (https://app.clearkm.com.br)
