# Política de Privacidade — AFA Point

**Última atualização:** 09 de abril de 2026

Esta Política de Privacidade descreve como o aplicativo **AFA Point** ("nós", "nosso" ou "aplicativo") coleta, usa, armazena e protege as informações dos usuários. Ao utilizar o aplicativo, você concorda com as práticas descritas neste documento.

---

## 1. Quem Somos

O **AFA Point** é um sistema de registro de ponto digital com reconhecimento facial, desenvolvido para uso corporativo em ambiente web e Android. O aplicativo é destinado exclusivamente a **adultos e colaboradores de organizações**, não sendo direcionado a crianças menores de 13 anos.

---

## 2. Dados Coletados

### 2.1 Dados Biométricos (Reconhecimento Facial)
- Imagens faciais capturadas pela câmera do dispositivo durante o processo de registro de ponto.
- Dados de geometria facial gerados a partir dessas imagens para fins de autenticação.

> **Atenção:** Dados biométricos são considerados dados sensíveis. Eles são coletados exclusivamente para autenticação do funcionário e **não são vendidos, compartilhados ou usados para fins publicitários**.

### 2.2 Dados de Identificação
- Nome completo do usuário.
- E-mail corporativo.
- Identificador único de usuário (UUID).
- Cargo e departamento (quando aplicável).

### 2.3 Dados de Registro de Ponto
- Data e hora dos registros de entrada e saída.
- Localização (quando autorizada pelo usuário e pela política da organização).

### 2.4 Dados de Dispositivo e Rede
- Informações sobre o dispositivo (modelo, versão do sistema operacional).
- Estado da conexão de rede (Wi-Fi / dados móveis) para fins de sincronização.

### 2.5 Dados de Uso
- Logs de acesso ao sistema para fins de auditoria e segurança.

---

## 3. Como Usamos os Dados

Os dados coletados são utilizados **exclusivamente** para:

| Finalidade | Base Legal |
|---|---|
| Autenticação e controle de acesso via reconhecimento facial | Execução de contrato / legítimo interesse |
| Registro e controle de jornada de trabalho | Obrigação legal (CLT / legislação trabalhista) |
| Geração de relatórios de presença para a organização | Execução de contrato |
| Segurança e prevenção de fraudes | Legítimo interesse |
| Comunicações relacionadas ao serviço | Execução de contrato |

---

## 4. Compartilhamento de Dados

**Não vendemos, alugamos nem comercializamos seus dados pessoais.**

Os dados podem ser compartilhados apenas com:

- **Supabase (infraestrutura de banco de dados em nuvem):** utilizado como backend para armazenamento seguro dos dados. O Supabase está em conformidade com as normas de segurança e privacidade aplicáveis. [Política de Privacidade do Supabase](https://supabase.com/privacy).
- **Gestores e RH da organização contratante:** acesso restrito aos registros de ponto dos colaboradores vinculados à organização.
- **Autoridades competentes:** quando exigido por lei ou ordem judicial.

---

## 5. Armazenamento e Segurança

- Os dados são armazenados em servidores seguros providos pelo **Supabase** com criptografia em repouso e em trânsito (TLS/HTTPS).
- O acesso ao banco de dados é protegido por chaves de autenticação (JWT) e políticas de segurança em nível de linha (Row Level Security — RLS).
- Imagens faciais são processadas localmente no dispositivo e apenas os vetores biométricos resultantes são armazenados, não as imagens brutas.
- Adotamos boas práticas de segurança da informação para proteger seus dados contra acesso não autorizado, perda ou alteração.

---

## 6. Permissões Solicitadas

O aplicativo solicita as seguintes permissões do dispositivo:

| Permissão | Motivo |
|---|---|
| **Câmera** | Captura de imagem facial para autenticação e registro de ponto |
| **Armazenamento (leitura/escrita)** | Armazenamento local de modelos de reconhecimento facial |
| **Internet** | Sincronização dos registros com o servidor |
| **Estado da rede / Wi-Fi** | Verificação de conectividade para sincronização |
| **Áudio** | Requerido pelo sistema em alguns dispositivos Android para acesso à câmera |

Todas as permissões são solicitadas apenas quando necessárias e podem ser revogadas pelo usuário nas configurações do dispositivo, o que pode limitar funcionalidades do aplicativo.

---

## 7. Retenção de Dados

- Os dados de registro de ponto são retidos pelo período exigido pela legislação trabalhista brasileira (mínimo de **5 anos**) ou pelo período contratado pela organização.
- Dados biométricos são retidos enquanto o vínculo empregatício estiver ativo e excluídos após o desligamento, salvo obrigação legal em contrário.
- Após o encerramento do contrato com a organização, os dados são anonimizados ou excluídos conforme solicitado.

---

## 8. Direitos do Usuário (LGPD)

Em conformidade com a **Lei Geral de Proteção de Dados (Lei nº 13.709/2018 — LGPD)**, você tem direito a:

- **Confirmar** a existência de tratamento dos seus dados.
- **Acessar** os dados que possuímos sobre você.
- **Corrigir** dados incompletos, inexatos ou desatualizados.
- **Solicitar a anonimização, bloqueio ou eliminação** de dados desnecessários ou tratados em desconformidade com a LGPD.
- **Portabilidade** dos dados a outro fornecedor de serviço, mediante requisição.
- **Revogar o consentimento** a qualquer momento.
- **Opor-se** ao tratamento realizado com fundamento em outras bases legais, em caso de descumprimento.

Para exercer seus direitos, entre em contato pelo e-mail indicado na seção **Contato**.

---

## 9. Público-Alvo

O **AFA Point** é destinado exclusivamente a **usuários adultos (18 anos ou mais)** no contexto corporativo. O aplicativo **não coleta dados de crianças menores de 13 anos**. Caso identificarmos que dados de menores foram coletados inadvertidamente, tomaremos as medidas cabíveis para a exclusão imediata desses dados.

---

## 10. Alterações nesta Política

Esta Política de Privacidade pode ser atualizada periodicamente. Notificaremos os usuários sobre alterações significativas por meio do próprio aplicativo ou por e-mail. Recomendamos revisar este documento regularmente.

---

## 11. Contato

Caso tenha dúvidas, solicitações ou queira exercer seus direitos relacionados à privacidade, entre em contato:

- **Aplicativo:** AFA Point
- **Pacote:** `com.afa.point`
- **E-mail para privacidade:** privacidade@afa.com.br *(atualize com o e-mail real da organização)*
- **Encarregado de Dados (DPO):** *(indique o nome e contato do DPO da organização, se aplicável)*

---

*Esta Política de Privacidade foi elaborada em conformidade com a Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018) e as diretrizes da Google Play para publicação de aplicativos.*
