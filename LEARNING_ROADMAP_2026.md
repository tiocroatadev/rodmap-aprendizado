# 🎯 Learning Roadmap 2026 - Cloud Solutions Architect Journey

**Status:** Active | **Duration:** 6 Months (Mar - Aug 2026) | **Last Updated:** Mar 31, 2026

---

## 📋 Overview

Estrutura de aprendizagem bi-diária para transição de NOC Team Leader → Cloud Solutions Architect.

**Objetivo Final:** AWS Solutions Architect Professional + IaC expertise + Linux administration + Basic Networking

---

## 🗓️ Timeline e Fases

```
FASE 1: ALICERCES (Semanas 1-4)
├─ AWS SAA C03 fundamentals
├─ Linux basics refresh
├─ Terraform basics
└─ Ansible basics

FASE 2: PROFUNDIDADE (Semanas 5-10)
├─ AWS SAA C03 aprofundado
├─ Linux intermediate
├─ Terraform applied (projetos reais)
├─ Ansible playbooks
└─ Cisco basic networking concepts

FASE 3: INTEGRAÇÃO (Semanas 11-16)
├─ AWS SAA C03 avançado + mock exams
├─ Linux administration real-world
├─ Projeto integrado: Infra as Code
├─ Ansible automation
├─ Cisco networking aplicado
└─ Inglês técnico consolidado

FASE 4: FINALIZAÇÃO (Semanas 17-24)
├─ AWS SAA C03 exame
├─ Projetos portfolio
├─ LinkedIn content
└─ Job search
```

---

## 📚 1. AWS CERTIFIED SOLUTIONS ARCHITECT - ASSOCIATE (C03)

### Objetivo
Certificação completa em AWS architecture, design, e best practices.

### Timeline
- **Start:** Week 1 (Semana de 31 Mar 2026)
- **Exam Target:** Week 18 (fins Ago 2026)
- **Study Time:** 1.5-2h/dia (componente principal)

### Roadmap Bi-Diário

#### **BLOCO 1: Fundamentals (Semanas 1-4)**

**Dia Par (2ª, 4ª, 6ª):**
- Core Services Deep Dive (2h)
  - Week 1: EC2, EBS, S3
  - Week 2: RDS, DynamoDB, ElastiCache
  - Week 3: VPC, Security Groups, NACLs
  - Week 4: ELB, Auto Scaling, CloudFront
- Lab prático (30 min)
- Review notas (15 min)

**Dia Ímpar (3ª, 5ª, 7ª):**
- Leitura AWS Whitepapers (1h)
- Hands-on Console (45 min)
- Quiz online (30 min)

**Objetivos Práticos:**
- Week 1: Deploy app em EC2 + S3 storage
- Week 2: Setup RDS database + backup
- Week 3: Create VPC multi-subnet + Security Groups
- Week 4: Setup ELB + Auto Scaling group

---

#### **BLOCO 2: Design Patterns (Semanas 5-10)**

**Dia Par:**
- Architecture patterns (2h)
  - Week 5: High Availability
  - Week 6: Disaster Recovery
  - Week 7: Cost Optimization
  - Week 8: Security & Compliance
  - Week 9: Migration strategies
  - Week 10: Exam-style questions
- Case study analysis (30 min)

**Dia Ímpar:**
- Exam questions (1.5h)
  - 50-100 questions/dia
  - Foco em weak areas
- Review incorretas (45 min)

**Objetivos Práticos:**
- Week 5: Design HA architecture (multi-AZ)
- Week 6: Design DR plan (backup/restore)
- Week 7: Cost optimization exercise
- Week 8: Security audit de própria infra
- Week 9: Migration plan document
- Week 10: 150+ exam questions acumuladas

---

#### **BLOCO 3: Mock Exams & Finalização (Semanas 11-18)**

**Dia Par:**
- Mock exams completos (3h)
  - 2 exames/semana, full conditions
  - Review detalhado de cada resposta

**Dia Ímpar:**
- Review weak areas (2h)
- Last-minute topics (1h)
- Relaxation/review anterior (exam weeks 17-18)

**Objetivos Práticos:**
- Week 11-16: 12+ mock exams (target: 80%+ score)
- Week 17: Refresh quick review
- Week 18: EXAM

---

### Recursos Recomendados

| Recurso | Tipo | Custo | Qualidade | Priority |
|---------|------|-------|-----------|----------|
| A Cloud Guru | Video + Labs | €15/mês | ⭐⭐⭐⭐⭐ | 1 |
| Linux Academy | Video + Labs | €15/mês | ⭐⭐⭐⭐⭐ | 1 |
| AWS Whitepapers | Official Docs | Free | ⭐⭐⭐⭐ | 2 |
| Exam Topaz | Practice Exams | €40 one-time | ⭐⭐⭐⭐ | 1 |
| TutorialDojo | Practice Exams | €15 one-time | ⭐⭐⭐⭐ | 2 |
| AWS Official | Documentation | Free | ⭐⭐⭐ | 3 |

---

### Tópicos Críticos (Memorizar)

- [ ] EC2 instance types (t3, m5, c5, r5, i3, etc.)
- [ ] RDS multi-AZ vs Read Replicas
- [ ] S3 storage classes (Standard, IA, Glacier, Deep Archive)
- [ ] VPC components (subnets, route tables, NAT, bastion)
- [ ] IAM permissions hierarchy
- [ ] CloudFront vs CloudFlare vs S3 distribution
- [ ] Load Balancer types (ALB, NLB, CLB) e quando usar
- [ ] Auto Scaling policies e metrics
- [ ] EBS volume types (gp3, io1, st1, sc1)
- [ ] Route 53 routing policies
- [ ] Lambda @ Edge vs CloudFront functions

---

## 🐧 2. LINUX ADMINISTRATION

### Objetivo
Voltar a estar fluente em Linux, administração prática, scripting básico.

### Timeline
- **Start:** Week 1
- **Duration:** 6 meses (paralelo a AWS)
- **Study Time:** 1h/dia (dias sem AWS SAA)

### Roadmap Bi-Diário

#### **BLOCO 1: Fundamentals Refresh (Semanas 1-4)**

**Dia Par:**
- Basics review (1h)
  - Week 1: File system, permissions, users/groups
  - Week 2: Process management, services, systemd
  - Week 3: Package management (apt, yum, dnf)
  - Week 4: Disk management, partitions, LVM
- Lab on own machine (30 min)

**Dia Ímpar:**
- Hands-on exercises (1h)
  - CLI drills (50 exercícios/semana)
  - Scripting basic (10 scripts/semana)

**Objetivos Práticos:**
- Week 1: Criar users/groups, alterar permissões, sudo config
- Week 2: Kill process, restart service, enable/disable services
- Week 3: Install package, uninstall, check dependencies
- Week 4: Create partition, format, mount filesystem

---

#### **BLOCO 2: Intermediate (Semanas 5-10)**

**Dia Par:**
- Advanced topics (1.5h)
  - Week 5: Shell scripting (bash)
  - Week 6: Text processing (grep, sed, awk)
  - Week 7: Networking (ifconfig, ss, netstat, iptables basics)
  - Week 8: System monitoring (top, htop, ps, iostat)
  - Week 9: Logging (syslog, journalctl, log rotation)
  - Week 10: Performance tuning basics

**Dia Ímpar:**
- Scripting practice (1.5h)
  - Week 5-10: Escrever 2 scripts úteis/semana

**Objetivos Práticos:**
- Week 5: Script de backup automático
- Week 6: Script de log parsing + alertas
- Week 7: Configure firewall rules, network troubleshooting
- Week 8: Create monitoring dashboard (Prometheus basics)
- Week 9: Setup log rotation + analysis
- Week 10: Performance baseline do sistema

---

#### **BLOCO 3: System Administration (Semanas 11-16)**

**Dia Par:**
- Real-world administration (1.5h)
  - Week 11: SSH keys, SSH hardening
  - Week 12: User/group policies, sudo rules
  - Week 13: Cron jobs, at, systemd timers
  - Week 14: Backup strategies (rsync, tar, snapshots)
  - Week 15: Security (fail2ban, SELinux basics)
  - Week 16: Documentation + best practices

**Dia Ímpar:**
- Troubleshooting exercises (1h)
  - Debug 5 common issues/semana
  - Write runbook pra cada

**Objetivos Práticos:**
- Week 11: SSH key-based auth + disable passwords
- Week 12: Create admin user com limited sudo
- Week 13: Setup cron job para manutenção
- Week 14: Automated backup script
- Week 15: Hardened server configuration
- Week 16: Complete sysadmin playbook pessoal

---

### Resources

| Recurso | Tipo | Link |
|---------|------|------|
| Linux Academy | Structured | linuxacademy.com |
| TryHackMe Linux | Interactive | tryhackme.com (Linux path) |
| DigitalOcean Tutorials | Practical | digitalocean.com/community |
| Linux Man Pages | Reference | man7.org |

### Critical Topics

- [ ] File permissions (umask, chmod, chown)
- [ ] User/group management (useradd, groupadd, sudoers)
- [ ] Process management (ps, kill, jobs, fg, bg)
- [ ] Package management em 2 distros (apt e yum)
- [ ] systemd (start, stop, enable, disable, status, journal)
- [ ] Bash scripting (variables, loops, functions, error handling)
- [ ] sed/awk (text processing)
- [ ] iptables basics (firewall rules)
- [ ] SSH hardening
- [ ] Cron vs systemd timers
- [ ] Disk/partition management (fdisk, lvm)

---

## 🔐 3. CISCO NETWORKING BASICS

### Objetivo
Entender conceitos de redes, NOT Cisco CLI (hate). Foco em concepts, topologia, protocolo.

### Timeline
- **Start:** Week 5 (depois de AWS + Linux basics)
- **Duration:** 8 semanas
- **Study Time:** 45 min/dia (3-4x/semana)

### Roadmap Bi-Diário

#### **BLOCO 1: Networking Fundamentals (Semanas 5-8)**

**Dia Par (2x/semana, 45 min):**
- Conceptual learning (30 min)
  - Week 5: OSI model, TCP/IP stack
  - Week 6: IP addressing, subnetting, CIDR
  - Week 7: Routing basics, static vs dynamic
  - Week 8: Switching, VLANs, STP
- Diagram/exercise (15 min)

**Dia Ímpar (1x/semana, 45 min):**
- Hands-on subnetting (30 min)
- Practical scenario (15 min)

**Objetivos Práticos:**
- Week 5: Desenha OSI model com protocolos em cada layer
- Week 6: Subnetwork 10.0.0.0/24 em 4 redes iguais
- Week 7: Desenha routing table, trace packet path
- Week 8: Design VLAN topology para empresa

---

#### **BLOCO 2: Cloud Networking Context (Semanas 9-12)**

**Dia Par (1x/semana, 45 min):**
- Concepts em contexto cloud (30 min)
  - Week 9: VPC parallels with VLAN/Subnetting
  - Week 10: Security Groups vs firewalls
  - Week 11: NAT, port forwarding, bastion hosts
  - Week 12: Multi-region/hybrid networking
- AWS practical (15 min)

**Objetivos Práticos:**
- Week 9: Design AWS VPC matching networking concepts
- Week 10: Create security group rules based on firewall rules
- Week 11: Configure NAT gateway + bastion host
- Week 12: Design hybrid on-premise to AWS network

---

### Resources (SEM Cisco CLI Pesado)

| Recurso | Tipo | Focus | Link |
|---------|------|-------|------|
| CompTIA Network+ | Video | Concepts not CLI | professor.messer.com |
| TryHackMe Network | Interactive | Hands-on concepts | tryhackme.com |
| Cisco Learning Network | Official | CCNA Fundamentals | learningnetwork.cisco.com |
| AWS VPC Deep Dive | Cloud-focused | VPC + networking | aws.amazon.com docs |

### Critical Topics

- [ ] OSI 7 layers + TCP/IP model
- [ ] IP addressing classes + CIDR notation
- [ ] Subnetting (calculate networks, hosts, broadcast)
- [ ] Routing (static, dynamic, default gateway)
- [ ] Switching + VLANs
- [ ] ARP (Address Resolution Protocol)
- [ ] DHCP
- [ ] DNS
- [ ] TCP vs UDP
- [ ] Port numbers (common ports 22, 80, 443, 3306, etc.)
- [ ] Firewall rules + ACLs (concepts, not CLI)

### ⚠️ NÃO Estuda

- Cisco CLI (te dá pavor, skip)
- EIGRP/OSPF deeply (over-spec)
- BGP (não precisa agora)
- Cisco proprietary protocols

---

## 🏗️ 4. TERRAFORM

### Objetivo
IaC profissional: escrever, testar, deploy infraestrutura como código.

### Timeline
- **Start:** Week 1
- **Duration:** 6 meses (paralelo)
- **Study Time:** 1h/dia (dias alternados)

### Roadmap Bi-Diário

#### **BLOCO 1: Fundamentals (Semanas 1-4)**

**Dia Par:**
- Learn HCL + core concepts (1h)
  - Week 1: Syntax, variables, outputs, state
  - Week 2: Resources, data sources, modules
  - Week 3: Provisioners, locals, count/for_each
  - Week 4: Workspaces, backends, best practices
- Write simple code (30 min)

**Dia Ímpar:**
- Hands-on (1h)
  - Week 1: Create simple VPC in Terraform
  - Week 2: Add EC2 + RDS from code
  - Week 3: Create reusable module
  - Week 4: Setup remote state

**Objetivos Práticos:**
- Week 1: Simple VPC setup in Terraform
- Week 2: Complete app infrastructure (VPC + EC2 + RDS)
- Week 3: Refactor to modules (VPC module, compute module)
- Week 4: Move state to remote backend (S3 + DynamoDB)

---

#### **BLOCO 2: Applied (Semanas 5-10)**

**Dia Par:**
- Advanced patterns (1.5h)
  - Week 5: Multiple regions/environments
  - Week 6: Module composition, dependencies
  - Week 7: Conditional logic, dynamic blocks
  - Week 8: Testing (tflint, checkov)
  - Week 9: CI/CD integration (GitHub Actions)
  - Week 10: State management, refactoring
- Code review own work (30 min)

**Dia Ímpar:**
- Real projects (1.5h)
  - Week 5: Deploy multi-region app
  - Week 6: Create 5+ reusable modules
  - Week 7: Complex architecture in code
  - Week 8: Test infrastructure code
  - Week 9: Setup automated deploy pipeline
  - Week 10: Refactor legacy Terraform code

**Objetivos Práticos:**
- Week 5: Multi-region WordPress + database
- Week 6: Module library (vpc, compute, database, monitoring)
- Week 7: Complex pattern (blue/green deployment)
- Week 8: Linted + tested Terraform code
- Week 9: GitOps pipeline (push → apply)
- Week 10: Clean, documented, production-ready code

---

#### **BLOCO 3: Mastery (Semanas 11-16)**

**Dia Par:**
- Advanced topics (1.5h)
  - Week 11: Terraform Cloud / Enterprise
  - Week 12: Cost estimation + optimization
  - Week 13: Integration with other tools (Ansible, Packer)
  - Week 14: Migration strategies
  - Week 15: Disaster recovery automation
  - Week 16: Documentation + knowledge share
- Code challenge (30 min)

**Dia Ímpar:**
- Portfolio projects (2h)
  - Week 11: Setup Terraform Cloud org
  - Week 12: Cost-optimized architecture
  - Week 13: Full CI/CD with IaC
  - Week 14: Migration automation
  - Week 15: DR automated failover
  - Week 16: Complete infrastructure documentation

**Objetivos Práticos:**
- Week 11: Production Terraform Cloud workspace
- Week 12: Cost report + optimization done
- Week 13: Full automation from code to production
- Week 14: Migration playbook + execution
- Week 15: Automated DR tests
- Week 16: Public documentation (GitHub + blog post)

---

### Resources

| Recurso | Tipo | Link |
|---------|------|------|
| Terraform Learn | Official | learn.hashicorp.com/terraform |
| A Cloud Guru | Structured | acloudguru.com |
| Linux Academy | Labs | linuxacademy.com |
| TerraForm Registry | Reference | registry.terraform.io |
| Terraform Best Practices | Book | terraform-best-practices.com |

### Critical Topics

- [ ] HCL syntax (resources, data, variables, outputs)
- [ ] State management (local, remote, locking)
- [ ] Modules (structure, composition, reusability)
- [ ] Workspaces (dev, staging, prod)
- [ ] count vs for_each (when to use each)
- [ ] Provisioners (remote-exec, local-exec)
- [ ] Data sources (existing resources)
- [ ] Locals + variables (best practices)
- [ ] Backends (S3, Terraform Cloud)
- [ ] Testing (tflint, checkov, terratest)
- [ ] CI/CD integration
- [ ] Cost optimization (instance sizing, reserved instances)

---

## 🤖 5. ANSIBLE

### Objetivo
Configuration management + automation. Complemento a Terraform.

### Timeline
- **Start:** Week 5 (depois basics)
- **Duration:** 8 semanas
- **Study Time:** 45 min/dia (2x/semana)

### Roadmap Bi-Diário

#### **BLOCO 1: Fundamentals (Semanas 5-8)**

**Dia Par (1x/semana, 45 min):**
- Learn YAML + core concepts (30 min)
  - Week 5: YAML syntax, inventory, ad-hoc commands
  - Week 6: Playbooks, tasks, handlers
  - Week 7: Roles, variables, loops, conditionals
  - Week 8: Best practices, structure, documentation
- Hands-on (15 min)

**Dia Ímpar (1x/semana, 45 min):**
- Hands-on (30 min)
  - Deploy simple playbook
  - Configure servers

**Objetivos Práticos:**
- Week 5: Setup Ansible on Linux machine + connect to 2+ hosts
- Week 6: Create playbook que instala e configura app
- Week 7: Create reusable role (web server role)
- Week 8: Full playbook with handlers + idempotence

---

#### **BLOCO 2: Applied (Semanas 9-12)**

**Dia Par (1x/semana, 45 min):**
- Advanced patterns (30 min)
  - Week 9: Multiple environments
  - Week 10: Complex roles, dependencies
  - Week 11: Integration with Terraform
  - Week 12: Testing + CI/CD
- Real exercise (15 min)

**Dia Ímpar (1x/semana, 45 min):**
- Projects (30 min)
  - Week 9: Deploy same config across 5+ servers
  - Week 10: Role composition (networking + security)
  - Week 11: Terraform output → Ansible inventory
  - Week 12: Automated testing of playbooks

**Objetivos Práticos:**
- Week 9: Multi-environment playbook (dev/staging/prod)
- Week 10: Complex role library (5+ reusable roles)
- Week 11: Terraform provisioning → Ansible configuration
- Week 12: Test playbooks automatically

---

### Resources

| Recurso | Tipo | Link |
|---------|------|------|
| Ansible Official | Docs | docs.ansible.com |
| Linux Academy | Courses | linuxacademy.com |
| TryHackMe Ansible | Interactive | tryhackme.com |
| Ansible Best Practices | Guide | ansible.com/resources |

### Critical Topics

- [ ] YAML syntax (indentation, data structures)
- [ ] Inventory (hosts, groups, variables)
- [ ] Ad-hoc commands (quick tasks)
- [ ] Playbooks (structure, execution)
- [ ] Tasks (modules, handlers)
- [ ] Roles (organization, reusability)
- [ ] Variables (facts, defaults, extra vars)
- [ ] Loops (with_items, loop)
- [ ] Conditionals (when, failed_when)
- [ ] Handlers (idempotence)
- [ ] Jinja2 templating
- [ ] Error handling

---

## 🌐 6. ENGLISH - TECHNICAL

### Objetivo
Fluidez em inglês técnico: ler docs, escrever posts, comunicação profissional.

### Timeline
- **Start:** Week 1
- **Duration:** 6 meses (contínuo)
- **Study Time:** 30 min/dia (5x/semana)

### Roadmap Bi-Diário

#### **BLOCO 1: Reading + Vocabulary (Semanas 1-4)**

**Dia Par (3x/semana, 30 min):**
- Read technical docs (15 min)
  - AWS documentation
  - Terraform guides
  - Kubernetes docs
- Vocabulary building (15 min)
  - Flashcards (Anki): 20 new words/dia
  - AWS terminology

**Dia Ímpar (2x/semana, 30 min):**
- Writing practice (20 min)
  - Translate Portuguese docs to English
  - Write short tech summaries
- Listening (10 min)
  - YouTube tech tutorials
  - AWS webinars

---

#### **BLOCO 2: Speaking + Writing (Semanas 5-10)**

**Dia Par (3x/semana, 40 min):**
- Writing technical content (20 min)
  - LinkedIn posts em inglês
  - GitHub documentation
  - Blog posts
- Pronunciation + speaking (20 min)
  - Record yourself explaining concepts
  - Shadowing (repeat after native speakers)

**Dia Ímpar (2x/semana, 30 min):**
- Conversation practice (20 min)
  - Language exchange (1:1 conversation, 2x/semana)
  - Discord tech communities
- Industry content (10 min)
  - Listen podcasts (DevOps, Cloud)

---

#### **BLOCO 3: Fluency (Semanas 11-16)**

**Dia Par (3x/semana, 40 min):**
- Advanced writing (20 min)
  - Technical documentation
  - Case studies
  - Position papers
- Speaking confidence (20 min)
  - Webinar participation
  - Presentation practice

**Dia Ímpar (2x/semana, 40 min):**
- Networking communication (20 min)
  - Comment on LinkedIn posts
  - Technical discussions
  - Twitter/X tech discussions
- Advanced listening (20 min)
  - Conferences (online)
  - Expert interviews

---

### Resources

| Recurso | Tipo | Focus | Link |
|---------|------|-------|------|
| Anki | Flashcards | Tech vocabulary | ankiweb.net |
| AWS Docs | Official | Reading + context | aws.amazon.com |
| Tandem | App | Language exchange | tandemapp.com |
| iTalki | Tutor | 1:1 conversation | italki.com |
| Podcast | Audio | Tech/Industry | podcastaddict.com |

### Critical Topics

- [ ] AWS terminology (availability zone, auto-scaling, etc.)
- [ ] Terraform language + documentation
- [ ] Ansible concepts em inglês
- [ ] Technical writing conventions
- [ ] Present tense for documentation
- [ ] Imperative for instructions
- [ ] Conditional language (if, when, should)
- [ ] Common tech phrases ("scale horizontally", "failover", etc.)
- [ ] Professional communication patterns
- [ ] Listening to native speakers

### Tracking

**Weekly word count (LinkedIn posts + docs):**
- Week 1-4: 500-1000 words/semana
- Week 5-10: 1000-2000 words/semana
- Week 11-16: 2000+ words/semana

**Target TOEFL/IELTS Score (if needed):**
- Technical C1 level (6+ IELTS / 100+ TOEFL)

---

## 🎯 Daily/Weekly Schedule Template

### Example Week (Semana Tipo)

**Segunda (Par Days):**
- [ ] AWS SAA (2h): EC2 deep dive + lab
- [ ] Linux (1h): User management practical
- [ ] Terraform (1h): Write simple module
- [ ] Inglês (30 min): Read AWS docs + vocabulary

**Terça (Ímpar Days):**
- [ ] AWS SAA (1.5h): Exam questions + review
- [ ] Ansible (45 min): Learn playbooks
- [ ] Linux scripting (30 min): Write backup script
- [ ] Inglês (30 min): Write LinkedIn post draft

**Quarta (Par Days):**
- [ ] AWS SAA (2h): Design patterns + labs
- [ ] Cisco Networking (45 min): Subnetting practice
- [ ] Terraform (1h): Project work
- [ ] Inglês (30 min): Vocabulary + listening

**Quinta (Ímpar Days):**
- [ ] AWS SAA (1.5h): Exam questions
- [ ] Linux (1h): System admin tasks
- [ ] Ansible (45 min): Playbook project
- [ ] Inglês (30 min): Conversation practice

**Sexta (Par Days):**
- [ ] AWS SAA (2h): Architecture patterns + labs
- [ ] Terraform (1h): Code review + testing
- [ ] Cisco (45 min): Concepts review
- [ ] Inglês (30 min): LinkedIn post final

**Sábado (Ímpar Days):**
- [ ] AWS SAA (1.5h): Mock exam 50-100 questions
- [ ] Linux (1h): Deep dive advanced topic
- [ ] Portfolio work (1h): GitHub update
- [ ] Inglês (30 min): Podcast + notes

**Domingo:**
- [ ] Weekly review (2h)
  - What learned?
  - What stuck?
  - Next week adjustments
- [ ] Admin (30 min)
  - Update progress tracker
  - Plan next week
  - Social media content prep

---

## 📊 Progress Tracking

### AWS SAA C03
```
Week 1: Fundamentals (EC2, S3, RDS)        ░░░░░░░░░░ 0%
Week 2: More services (VPC, ELB)           ░░░░░░░░░░ 0%
Week 3: Design patterns                    ░░░░░░░░░░ 0%
...
Week 18: EXAM TARGET DATE                  ░░░░░░░░░░ EXAM
```

### Linux
```
Week 1-4: Fundamentals                     ░░░░░░░░░░ 0%
Week 5-10: Intermediate                    ░░░░░░░░░░ 0%
Week 11-16: Administration                 ░░░░░░░░░░ 0%
```

### Terraform
```
Week 1-4: Learn HCL                        ░░░░░░░░░░ 0%
Week 5-10: Projects                        ░░░░░░░░░░ 0%
Week 11-16: Mastery + portfolio            ░░░░░░░░░░ 0%
```

### Ansible
```
Week 5-8: Fundamentals                     ░░░░░░░░░░ 0%
Week 9-12: Applied                         ░░░░░░░░░░ 0%
```

### Cisco Networking
```
Week 5-8: Concepts                         ░░░░░░░░░░ 0%
Week 9-12: Cloud context                   ░░░░░░░░░░ 0%
```

### English
```
Vocabulary: 0/500 words
Speaking hours: 0/50 hours
Writing: 0 posts
Listening hours: 0/30 hours
```

---

## 🧠 Soft Skills Para Incluir

### 1. **COMUNICAÇÃO TÉCNICA (Critical)**

**O que:** Explicar conceitos complexos de forma simples.

**Por quê:** Architects precisam comunicar com C-level, ops teams, devs. Precisas conseguir explicar design decisions.

**Como desenvolver:**
- Write 1 technical blog post/semana em inglês (explain what learned)
- Record yourself explaining architecture (30 min/semana)
- Present designs to imaginary audience (talk out loud)

**Time Investment:** 1-2h/semana extra

---

### 2. **PROBLEM SOLVING / CRITICAL THINKING (Critical)**

**O que:** Quebrar problemas complexos em peças menores, pensar trade-offs.

**Por quê:** Architecture is about trade-offs. Cost vs. performance. Simplicity vs. features.

**Como desenvolver:**
- Read case studies (AWS, others), analyze decisions
- When building projects, document WHY escolheste essa solução
- Ask "what could go wrong?" in every design
- Challenge own decisions (play devil's advocate)

**Time Investment:** Embedded nos projetos (0 extra)

---

### 3. **DOCUMENTATION (High)**

**O que:** Escrever documentação clara, diagrams, runbooks.

**Por quí:** Architecture que não está documentado não existe. Teams precisam entender.

**Como desenvolver:**
- Document EVERYTHING que estuda
- Create diagrams (Lucidchart, Draw.io) for every architecture
- Write README para cada projeto
- Create runbooks para operações

**Time Investment:** 30 min/projeto extra

---

### 4. **OWNERSHIP / ACCOUNTABILITY (High)**

**O que:** Take responsibility, deliver, follow through.

**Por quê:** Saíste de "blaming operations" mindset. Architects own decisions.

**Como desenvolver:**
- Complete projects fully (não half-measures)
- When wrong, own it, fix it, document lesson
- Follow through on commitments
- Track own progress publicly (LinkedIn)

**Time Investment:** Mindset change (0 extra)

---

### 5. **CONTINUOUS LEARNING (High)**

**O que:** Curiosity, staying updated, reading, experimenting.

**Por quê:** Cloud moves fast. Architectures evolve.

**Como desenvolver:**
- Read 1 AWS blog post/semana
- Follow tech leaders on Twitter/LinkedIn
- Experiment with new AWS services
- Participate in tech communities

**Time Investment:** 1-2h/semana

---

### 6. **LEADERSHIP (Medium)**

**O que:** Guide teams, make decisions, mentor others.

**Por quê:** Team Leader → need leadership skills actually.

**Como desenvolver:**
- Write posts/docs that teach others
- Help 1 person/semana with technical question
- Lead design discussions (not decisions, discussions)
- Mentor someone junior (peer mentoring)

**Time Investment:** 1-2h/semana

---

### 7. **BUSINESS ACUMEN (Medium)**

**O que:** Understand business impact, costs, ROI.

**Por quê:** Architecture decisions have business implications.

**Como desenvolver:**
- Every project must have cost estimate
- Understand pricing (compute, storage, data transfer)
- Think about revenue impact (uptime, performance)
- Learn about company metrics (churn, CAC, LTV)

**Time Investment:** Embedded (0 extra)

---

### 8. **ATTENTION TO DETAIL (Medium)**

**O que:** Catch errors, follow best practices, documentation accuracy.

**Por quí:** One security mistake = breach.

**Como desenvolver:**
- Code review próprio trabalho before shipping
- Checklist antes de deploy (security, performance, cost)
- Test everything twice
- Audit own deployments

**Time Investment:** 30 min/project

---

### 9. **ADAPTABILITY / FLEXIBILITY (Medium)**

**O que:** Adjust to changes, new tools, different contexts.

**Por quê:** Cloud platforms change. Requirements change.

**Como desenvolver:**
- Learn tools quickly (new AWS services)
- Be comfortable with ambiguity
- Prototype before committing
- Embrace change

**Time Investment:** Mindset (0 extra)

---

### 10. **HUMILITY (Low-Medium but Important)**

**O que:** Admit quando não sabes, ask for help, learn from others.

**Por quê:** Egocentric architects make bad decisions.

**Como desenvolver:**
- Share mistakes publicly (learn from failures)
- Ask questions in tech communities
- Acknowledge good ideas from others
- Change mind when evidence suggests

**Time Investment:** Mindset (0 extra)

---

## 🚨 Hard Skills - Is There Anything Missing?

### Análise de Gaps

**What's covered:**
- ✅ Cloud architecture (AWS SAA C03)
- ✅ Infrastructure as Code (Terraform)
- ✅ Configuration management (Ansible)
- ✅ Systems administration (Linux)
- ✅ Networking fundamentals (Cisco basics)
- ✅ English technical

**What's NOT covered (but Optional):**

| Skill | Relevance | Priority | Notes |
|-------|-----------|----------|-------|
| Docker | High | Consider adding Week 13+ | Containers are critical for modern infra |
| Kubernetes | High | Consider adding Week 14+ | K8s is industry standard (CKA not needed now) |
| Git/GitHub | High | MUST add Week 1 | You need version control for Terraform |
| Monitoring (Prometheus) | Medium | Consider Week 12+ | Observability skills |
| CI/CD (GitHub Actions) | Medium | Consider Week 9+ | DevOps integration |
| Security (IAM, Secrets) | High | Embedded in AWS SAA | Covers basics, deeper study optional |
| Python scripting | Low | Optional | Useful but not critical |
| SQL/Databases | Medium | AWS SAA covers | Deeper knowledge optional |
| Packer | Low | Optional | Infrastructure image building |
| Vault | Low | Optional | Secrets management |

### Recomendação: Add 2 Skills

**1. Docker (1-2 weeks, Week 13)**
- Understand containers, Dockerfiles, images, registries
- Time: 6-8h total
- Why: Modern architecture relies on containers
- Integration: Pair with Ansible (container deployment)

**2. Git/GitHub (Week 1, Parallel)**
- Git basics, workflow, GitHub workflow
- Time: 4-6h total
- Why: CRITICAL for Terraform, collaboration
- Integration: All code goes to GitHub

**Otherwise you're well-covered.**

---

## 📈 Success Metrics

### By Week 18 (End of Program), Target:

**AWS SAA C03:**
- [ ] Exam passed (score 80%+)
- [ ] 2-3 production-ready architectures designed
- [ ] 10+ case study analyses documented

**Linux:**
- [ ] Comfortable with bash scripting
- [ ] Can admin server from scratch
- [ ] 10+ automation scripts created
- [ ] All documentation written

**Terraform:**
- [ ] GitHub repo com 5+ production modules
- [ ] Full CI/CD pipeline working
- [ ] Can refactor legacy infra
- [ ] Portfolio quality code

**Ansible:**
- [ ] 2+ playbooks covering real scenarios
- [ ] Integration with Terraform proven
- [ ] Testing framework in place

**Cisco Networking:**
- [ ] Understands subnetting, routing, VLANs
- [ ] Can design network topology
- [ ] AWS VPC mapping fluent

**English:**
- [ ] 16+ technical posts published
- [ ] Can present architecture design in English
- [ ] Comfortable with technical docs
- [ ] B2/C1 confidence level

**Soft Skills:**
- [ ] 16+ blog posts (communication)
- [ ] 2+ public projects (accountability)
- [ ] 1 person mentored (leadership)
- [ ] 100+ hours learning (continuous learning)

---

## 🎬 Getting Started - Today

### Today's Action Items:

1. **Clone this repo** (or add to your existing learning repo)
2. **Create GitHub Issues** for each week (auto-track progress)
3. **Setup Anki** para vocabulary
4. **Subscribe to:**
   - A Cloud Guru (€15/mês)
   - Linux Academy (€15/mês)
5. **Start Week 1, Day 1:**
   - [ ] First AWS SAA video (30 min)
   - [ ] First Linux refresher (30 min)
   - [ ] First Terraform tutorial (30 min)
   - [ ] Vocabulary first 20 words (20 min)

**Total:** 2h today.

---

## 📝 Notes

- **Flexibility:** If one area takes longer, adjust others. Not rigid, adaptive.
- **Quality over speed:** 1 good project > 5 half-done projects
- **Visibility:** Document everything, share progress
- **Accountability:** Public commitment > private goals
- **Community:** Find study partners, share learning

---

## 🤝 Contributing / Updating

This roadmap is **living document**. Update as you learn:
- [ ] Add resources that worked
- [ ] Remove resources that didn't
- [ ] Adjust timeline based on real progress
- [ ] Share wins and failures

---

**Last Updated:** Mar 31, 2026
**Next Review:** Apr 28, 2026

---

**Good luck. You've got this. 🚀**
