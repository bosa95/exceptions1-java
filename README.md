Solução 1 (muito ruim):</br> 
• Lógica de validação no programa principal</br> 
• Lógica de validação não delegada à reserva

Solução 2 (ruim): </br> 
• Método retornando string </br> 
• A semântica da operação é prejudicada</br> 
• Retornar string não tem nada a ver com atualização de reserva</br> 
• E se a operação tivesse que retornar um string?</br> 
• Ainda não é possível tratar exceções em construtores</br> 
• Ainda não há auxílio do compilador: o programador deve "lembrar" de verificar se houve
erro</br> 
• A lógica fica estruturada em condicionais aninhadas

Solução 3 (boa): </br> 
• Tratamento de exceções
