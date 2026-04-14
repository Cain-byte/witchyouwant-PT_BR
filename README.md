📁 No ../games/screens.rpy, eu adicionei a seguinte linha de código para opção ficar disponível:
```
#Menu de idiomas 
                vbox:
                    style_prefix "radio"
                    label _("Language")
                    textbutton "English" action Language(None)
                    textbutton "Português" action Language("portuguese")
```

📌Esta tradução não possui fins comerciais nem está associada aos criadores do jogo. Trata-se de um trabalho gratuito, feito por fãs para outros fãs. Pedimos que respeite a propriedade intelectual original e utilize os canais oficiais para adquirir o produto.
