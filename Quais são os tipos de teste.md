# Quais são os tipos de teste?

Testes de funcionalidade: Verifica se determinada funcionalidade tem o comportamento esperado. Um exemplo é um teste que tenta gerar a segunda via do boleto. O testador clica no botão de segunda via e verifica se o sistema gerou o arquivo corretamente.
Testes de usabilidade: Verifica características não-funcionais de usabilidade. É mais usado para compreender e melhorar a interação do usuário com o software, do que para ‘encontrar erros’. Valida questões como: Satisfação subjetiva dos usuários com o sistema e Facilidade de aprendizado para uso do sistema.
Testes de segurança: Avalia as vulnerabilidades do software para determinados tipos de ataques.
Testes de performance ou desempenho:  Avalia se o sistema atende requisitos de tempo de resposta, tempo para entrar em funcionamento e volume de uso.
Pela técnica empregada, podemos classificar em:

Teste funcional: black box, olha por fora mas não se importa com a estrutura interna. Tem por objetivo garantir que os requisitos e as especificações do sistema tenham sido corretamente implementados.
Teste estrutural: White box, olha por dentro, tentando garantir que a estrutura esteja correta. Tem como foco  averiguar o comportamento do sistema em determinadas situações garantindo que o software funcione no contexto técnico onde serão instalados.
Pelo nível em que o teste ocorre, podemos separar em:

Teste de unidade: Verifica uma unidade (a menor parte do software) para garantir que tem o comportamento esperado. Neste tipo de teste, a unidade é testada de forma isolada, sem considerar nenhuma dependência ou integração. Geralmente significa invocar um método passando determinadas entradas e então validar se a saída está correta.
Teste de integração: Verifica que uma unidade tem o comportamento esperado quanto funciona integrada com as partes das quais depende. Pode verificar a integração entre uma classe e o banco de dados, entre um módulo e um web service, etc.
Teste de sistema: Verifica se o sistema como um todo tem o comportamento esperado. Esse tipo de teste não está interessado nas partes e no comportamento individual das unidades, mas sim no resultado do todo. É um tipo de teste ‘black box’.
Teste de aceitação: É o mesmo que o teste de sistema, mas geralmente mais superficial, se preocupa em dizer se o sistema atende os requisitos mínimos para ser aceito, olhando o todo de forma ‘black box’.
