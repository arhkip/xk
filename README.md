
Calculadora Tk
Demo da calculadora
Motivação
O projeto tem por objetivo incentivar iniciantes na programação em python a contribuir com projetos open source que vão além do Terminal, de modo que seja mais visual o desenvolvimento.

Sendo assim, foi criado a Calculadora Tk com funcionalidades matemáticas básicas e com alguns erros propositais para que as correções e ampliações de novas funcionalidades sejam feitas pelo público alvo (Iniciantes).

Para contribuir
Siga os passos abaixo:

Faça o Fork do projeto Calculadora Tk no canto superior direito da tela;
Clone o projeto do seu repositório no github (git clone https://github.com/SEU_USUARIO/calculadora-tk.git);
Crie sua branch para realizar sua modificação (git checkout -b feature/nome_da_modificação);
Após ter realizado suas modificações, faça um commit (git commit -m "Descrição da modificação");
Faça o Push para seu repositório (git push origin feature/nome_modificação);
No seu repositório no Github crie uma Pull Request para que seja avaliada a suas modificações para ser feito o merge no projeto principal.
Contribuidores

@aguiarcandre	
@carlos3g	
@ericllma	
@sam-chami	
@taisbferreira	
@edilsonmatola

@maguzzz	
@vinayyak				
Para ideias/Bugs
Caso encontre algum bug crie uma issue descrevendo o Bug encontrado que tem que ser resolvido, informando o passo a passo para replicá-lo.

E caso tenha alguma ideia de nova funcionalidade que possa ser implementada por outros iniciantes, crie uma issue descrevendo essa ideia. ;)

Start
$ python main.py
ou crie seu próprio arquivo com o seguinte script, e depois siga o procedimento acima com o nome correspondente:

# -*- coding: utf-8 -*-

# Builtin
import tkinter as tk

# Internal module
from app.calculadora import Calculadora

if __name__ == '__main__':
    master = tk.Tk()
    main = Calculadora(master)
    main.start()
Guias
Tkinter: Documentação - Existe diversos outros guias em mostra logo no ínicio do página
Git e Github: Tutorial no Tableless - Leitura
Git e Github: Tutorial no Youtube - Vídeo Aula
Pull Request no GitHub: Tutorial DigitalOcean - Leitura
