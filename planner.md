# Planejamento Inicial - JULIEN

## Objetivo imediato
- Entregar uma interface grafica funcional.
- Permitir uma conversa simples com o Julien somente por voz (estilo Jarvis).

## Proxima acao obrigatoria
- [ ] Baixar e instalar o Ollama no Windows no ambiente local.
- [ ] Validar instalacao do Ollama (servico ativo e modelo carregado).

## Fase 1 - Fundacao do projeto
- [ ] Definir stack da interface grafica (ex.: Tkinter, PySide6 ou web com Streamlit).
- [ ] Estruturar pastas iniciais do projeto.
- [ ] Criar modulo de integracao com o Ollama.
- [ ] Definir stack de voz (captura de microfone, STT e TTS).

## Fase 2 - Conversa por voz com Julien
- [ ] Capturar audio do microfone com estabilidade.
- [ ] Transcrever fala do usuario (STT) para texto.
- [ ] Fazer chamada simples ao modelo no Ollama com o texto transcrito.
- [ ] Converter resposta do Julien em audio (TTS) e reproduzir para o usuario.
- [ ] Exibir feedback visual minimo (escutando, processando, respondendo).
- [ ] Tratar erros basicos (microfone indisponivel, Ollama offline, modelo nao encontrado, timeout).

## Fase 3 - Estilo Jarvis (iteracao inicial)
- [ ] Definir modo de ativacao por voz (palavra de ativacao ou botao de escuta).
- [ ] Ajustar latencia para manter conversa natural.
- [ ] Melhorar qualidade da voz de resposta do Julien.

## Criterio de sucesso desta etapa
- Interface abre sem erros.
- Usuario fala no microfone e recebe resposta em voz do Julien via Ollama.
- Fluxo minimo de conversa por voz funcionando de ponta a ponta.
