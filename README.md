# Atividade_helloWorld
Ruby on Rails - Arthur, Camile e João Dias
Pontos Fortes e Filosofia
•	Convenção sobre Configuração: Reduz a quantidade de decisões que os
        desenvolvedores precisam tomar, promovendo padrões consistentes.
•	DRY (Don't Repeat Yourself): Incentiva a reutilização de código e a
        redução de duplicações.
•	Foco na Produtividade do Desenvolvedor: Ferramentas integradas e uma
        comunidade ativa ajudam a acelerar o desenvolvimento.
•	Arquitetura MVC (Model-View-Controller): Promove a separação de
        preocupações, facilitando a manutenção e escalabilidade do código.
•	Gemas e Plugins: Uma vasta biblioteca de gemas permite adicionar
        funcionalidades rapidamente ao projeto.
Exemplo de Caso de Uso Ideal
Ruby on Rails é ideal para startups que desejam lançar produtos
      rapidamente no mercado, graças à sua ênfase na produtividade e convenções
      que aceleram o desenvolvimento.
Pré-Requisitos e Setup
•	Instalar Ubuntu: Certifique-se de ter uma versão atualizada do Ubuntu
        instalada.
•	Instalar Ruby: Certifique-se de ter a versão correta do Ruby instalada.
•	Instalar Rails: Use o comando `gem install rails` para instalar o
        framework Rails.
•	Comandos para Instalação atravez do terminal do Ubuntu:# Instala dependências com apt
                    sudo apt update
                    sudo apt install build-essential rustc libssl-dev libyaml-dev zlib1g-dev libgmp-dev
                    
                    # Instala Mise versão manager
                    curl https://mise.run | sh
                    echo 'eval "$(~/.local/bin/mise activate bash)"' >> ~/.bashrc
                    source ~/.bashrc
                    
                    # Instala Ruby globally com Mise
                    mise use -g ruby@3

                    # Instala Rails
                    gem install rails
O Código do Servidor

      rails new meu_projeto 
      cd meu_projeto
      
Instruções para Rodar o Servidor
1.	Inicie o servidor Rails com o comando:rails s
2.	Acesse a aplicação no navegador através do endereço:http://localhost:3000
Conclusão
Tivemos uma pequena dificuldade para encontrarmos um video tutorial mais
      simples, alguns ensinavam como criar um projeto completo com Banco de
      dados, que não era nosso objetivo. Mas conseguimos encontrar um video que
      explica os conceitos básicos do Ruby on Rails de forma clara e objetiva.
      (Link do vídeo
