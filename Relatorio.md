# Relatório de Visita Técnica à DIGTI/IFRN

**Disciplina:** Sistemas Operacionais  
**Curso:** Tecnologia em Análise e Desenvolvimento de Sistemas  
**Aluno:** [Seu Nome]  
**Data da Visita:** [dd/mm/aaaa]  
**Local Visitado:** Diretoria de Gestão de Tecnologia da Informação (DIGTI) - IFRN Campus Natal-Central  

---

## 1. Introdução

A DIGTI é o coração tecnológico do IFRN, responsável por manter sistemas como o SUAP, redes, servidores e toda a infraestrutura de TI que usamos diariamente. Confesso que estava ansioso para essa visita, pois queria entender como a teoria que vemos em sala - sobre gerência de processos, memória e virtualização - se aplica na prática. Apesar de ter ficado com algumas dúvidas (que vou mencionar mais adiante), a experiência foi super válida para conectar os conceitos da disciplina com o mundo real.

---

## 2. Descrição do Ambiente Visitado

### A Equipe da DIGTI

Ficamos sabendo que o time é dividido em várias áreas:
- **Administradores de Sistemas:** Os "mágicos" que cuidam dos servidores físicos e virtuais
- **Analistas de Redes:** Responsáveis por toda a parte de conectividade do campus
- **Suporte Técnico:** Quem resolve nossos problemas no dia a dia

### Como funciona a Infraestrutura

O que mais me chamou atenção:
- **SUAP:** Roda em vários servidores virtuais com balanceamento de carga
- **Virtualização:** Usam VMware para criar máquinas virtuais
- **Monitoramento:** Ferramentas como Zabbix ficam de olho em tudo

**Dúvidas que ficaram:**
- Como exatamente o balanceamento de carga decide qual servidor vai atender cada requisição?
- Qual a diferença prática de desempenho entre um servidor físico e um virtual?

---

## 3. Aprendizados e Destaques

### O que entendi bem ✅
- **Virtualização:** Economizam muito usando várias VMs num mesmo servidor físico
- **Segurança:** Usam um monte de camadas de proteção (firewalls, autenticação LDAP)
- **Backup:** Tem um sistema automático que salva tudo localmente e na nuvem

### O que não ficou tão claro ❌
- **Detalhes da rede:** Como configuram os equipamentos para evitar lentidão?
- **Contêineres:** Ouvi falar de Docker, mas não entendi como usam na prática
- **Emergências:** O que fazem quando um servidor importante cai?

### Desafios que me surpreenderam
- **Picos de acesso:** Nas épocas de matrícula o sistema sofre demais
- **Ataques:** Tem tentativas de invasão o tempo todo - achei que seria mais tranquilo

---

## 4. Considerações Finais

A visita me mostrou como a teoria de Sistemas Operacionais é importante no mundo real. Fiquei fascinado pela parte de virtualização, mas confesso que saí com mais perguntas do que respostas - especialmente sobre:

- Como é o trabalho diário dos administradores de sistemas
- Como configuram a rede para tantos usuários
- Quais são os planos para atualizar a infraestrutura

**O que faltou?** 
Achei que seria legal ver:
- Uma demonstração prática de como criar uma VM
- Como é a sala de servidores fisicamente
- Mais detalhes sobre carreira na área

No geral, valeu muito a pena, mesmo com as dúvidas que ficaram. Agora quando usar o SUAP vou lembrar de toda a complexidade por trás dele!

---

**Observação pessoal:**  
*"Depois dessa visita, fiquei pensando se um dia vou trabalhar num lugar assim... Será que deixariam um estagiário mexer nos servidores ou só olhar de longe?"* 😅
