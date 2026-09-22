# Documentação — Tarefa 33 (Página Pessoal com DaisyUI)

## 1. Componentes DaisyUI Utilizados
* **Navbar**: Utilizado na barra superior para identificação da página.
* **Hero**: Utilizado na seção inicial para destacar a mensagem de apresentação e chamada de ação.
* **Badge**: Utilizado na seção "Sobre Mim" para destacar habilidades (`badge-primary`, `badge-secondary`, `badge-accent`, `badge-outline`).
* **Card**: Utilizado na seção "Meus Projetos" estruturando três cards com `card-body` e `card-actions`.
* **Button (`btn`)**: Utilizado em botões de ação e dentro dos cards com diferentes estilos (`btn-primary`, `btn-secondary`, `btn-outline`).
* **Input**: Utilizado nos campos de formulário na seção de contato com a classe `input-bordered`.
* **Alert**: Utilizado para contextualizar a caixa de mensagens na seção de contato (`alert-info`).

## 2. Justificativas de Escolha
* **Navbar + Hero**: A combinação de uma `navbar` no topo com um bloco `hero` permite criar um cabeçalho claro e objetivo sem sobrecarregar visualmente o utilizador.
* **Cards para Projetos**: O formato `card` garante uma divisão semântica coerente para exibir diferentes trabalhos com o mesmo padrão visual.

## 3. Pontos de Ajuste com Tailwind CSS Pure
* **Grid e Espaçamento de Layout**: Foram utilizadas classes puras do Tailwind (ex: `grid grid-cols-1 md:grid-cols-3 gap-6`, `max-w-4xl mx-auto`, `py-12`) para gerir o alinhamento centralizado, a grelha de projetos e as margens entre as seções, visto que o DaisyUI foca na estilização individual de cada componente.

## 4. Reflexão sobre Temas (`data-theme`)
A página foi testada alterando a propriedade `data-theme` da tag `<html>` entre `light` e `dark`. A legibilidade manteve-se consistente em ambos os temas graças à utilização das variáveis semânticas de cor do DaisyUI (como `bg-base-100`, `bg-base-200` e `text-base-content`).