**Bold**Solução 1 (muito ruim): lógica de validação no programa principal</br> 
• Lógica de validação não delegada à reserva

**Bold**Solução 2 (ruim): método retornando string </br> 
• A semântica da operação é prejudicada</br> 
• Retornar string não tem nada a ver com atualização de reserva</br> 
• E se a operação tivesse que retornar um string?</br> 
• Ainda não é possível tratar exceções em construtores</br> 
• Ainda não há auxílio do compilador: o programador deve "lembrar" de verificar se houve
erro</br> 
• A lógica fica estruturada em condicionais aninhadas

**Bold**Solução 3 (boa): tratamento de exceções
