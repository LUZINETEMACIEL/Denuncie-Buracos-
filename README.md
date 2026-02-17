# 🕳️ Denuncie Buracos e Problemas na Via Pública - Prefeitura de Manaus

Uma solução web colaborativa para que cidadãos possam reportar problemas de infraestrutura em vias públicas, facilitando o mapeamento de buracos e danos em ruas e avenidas.

---

## 📝 Sobre o Projeto

Este projeto nasceu da necessidade de dar voz à comunidade. Através da plataforma, qualquer usuário pode registrar uma ocorrência de forma rápida, ajudando a criar um mapa visual dos pontos críticos que necessitam de manutenção asfáltica.

### ✨ Principais Funcionalidades
* **Registro de Ocorrências:** Formulário intuitivo para detalhar o problema.
* **Evidência Visual:** Upload de fotos para comprovar a situação real da via.
* **Detalhamento:** Campo de descrição para observações importantes (ex: profundidade, localização exata).
* **Interface Responsiva:** Otimizado para que o cidadão denuncie diretamente do celular enquanto está na rua.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend:** HTML5, CSS
* **Versionamento:** Git & GitHub

---

## 🧪 Garantia de Qualidade (QA) - Testes Manuais

Para garantir a confiabilidade do sistema e a integridade das denúncias, o projeto passou por um rigoroso processo de **QA com foco em testes manuais de inputs**.

### 🔍 Foco dos Testes de Entrada (Inputs)
* **Validação de Formulário:** Testes de tentativa de envio sem preenchimento de campos obrigatórios.
* **Tratamento de Imagens:** Verificação de formatos aceitos (JPG, PNG) e comportamento do sistema com arquivos de diferentes tamanhos.
* **Sanitização de Texto:** Testes para garantir que emojis e caracteres especiais na descrição sejam renderizados corretamente sem quebrar o layout.

### 📋 Matriz de Testes Realizados

| Cenário de Teste | Entrada (Input) | Comportamento Esperado | Status |
| :--- | :--- | :--- | :--- |
| Envio Incompleto | Clicar em enviar sem foto | Alerta solicitando a imagem obrigatória | ✅ Passou |
| Descrição com Emojis | "Buraco perigoso! ⚠️⚠️" | Texto exibido corretamente no dashboard | ✅ Passou |
| Upload de Arquivo Inválido | Arquivo .pdf ou .txt | Bloqueio imediato do upload com aviso | ✅ Passou |
| Teste de Responsividade | Uso via Smartphone | Botões e campos de input ajustados à tela | ✅ Passou |

---


