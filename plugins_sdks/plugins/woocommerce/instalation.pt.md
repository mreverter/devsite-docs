---
sites_supported:
  - mla
  - mlb
  - mco
  - mlu
  - mlm
  - mlc
---

# Instale o Mercado Pago no WooCommerce
<br/>

Instale o Mercado Pago no WooCommerce automaticamente pelo marketplace na WordPress ou manualmente, importando um arquivo .zip no seu diretório vía FTP.

> NOTE
>
> Nota
>
> A instalação do nosso módulo não afeta a velocidade da sua loja.

## Requisitos de instalação

Revise os requisitos de instalação e siga as etapas que indicamos. A instalação do módulo leva poucos minutos!

| Requisitos                    | Detalhes                                                                  	                  |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| Versões         	            | O módulo funciona para as versões do WordPress 3.1.x - 4.9.x y WooCommerce 2.6.x - 3.4.x      |
| Ambiente                    	| LAMP (Linux, Apache, MySQL, and PHP)                                                      	  |
| Sistema                     	| Linux x86, Windows x86-64                                                        	            |
| Servidor Web                	| Apache 2.x, Nginx 1.7.x                                                               	      |
| Versão PHP                  	| PHP 5.6 ou superior com suporte a curl                     	                                  |
| Base de dados               	| MySql 5.6 ou superior, MariaDB 10.0 ou superior                            	                  |
| Dependência de extensões     	| PDO_MySQL, simplexml, mcrypt, hash, GD, DOM, iconv, curl, SOAP (para Webservices API)         |
| Configuração adicional        | safe_mode off * memory_limite maior que 256MB (512MB recomendado)                             |
| SSL                         	| Certificado SSL  	                                                                            |

> WARNING
>
> Importante
>
> Você pode usar o protocolo HTTP no modo "Teste" e não fazer transações reais. Quando for a Produção, você deve ter um **certificado SSL** para oferecer **navegação segura** e proteger seus dados e os dos seus clientes. Depois, a rota de acesso para a sua loja virtual responderá ao **protocolo HTTPS**.

## Instalação Automática

### De forma automática, na seção “Plugins” do WordPress

Siga estas etapas para a instalação:

* Vá em **Adicionar** novo e pesquise “WooCommerce Mercado Pago” entre os módulos do WordPress.
* Clique em Instalar e depois busque a seção “Plugins Instalados”. 
* Ative-o para começar a configurar o módulo na sua loja.
* Excelente! Você já verá o módulo instalado na seção Plugins do seu painel. Ative-o para poder fazer as configurações necessárias na sua loja.

## Instalação manual

### De forma manual, instale o módulo em três etapas:

* Baixe o arquivo .zip no nosso repositório do Github ou no diretório de módulos de WordPress.
                    
> NOTE
>
> [Baixar](https://github.com/mercadopago/cart-woocommerce/archive/master.zip)
>
> [Módulo do Mercado Pago para WooCommerce](https://github.com/mercadopago/cart-woocommerce/archive/master.zip)

* Descompacte a pasta baixada e altere o nome para "woocommerce-mercadopago".
* Conecte-se ao seu servidor web e copie o arquivo "woocommerce-mercadopago" no seu diretório do WordPress, dentro da pasta "Plugins".
* Pronto! O módulo do Mercado Pago será instalado na sua loja virtual.

Confira se tudo está ok no seu painel do WordPress. Você verá o módulo nos seus Plugins instalados. Ative-o para passar para a integração da sua conta e etapas de configuração. 

Quando você ativar o plugin, o WordPress levará aos Ajustes do WooCommerce e depois para a seção de Payments, onde estão todos os tipos de checkout que oferecemos para sua loja virtual: Smart Checkout e Checkout Personalizado.

> NOTE
>
> Nota
> 
> Todos os nossos módulos contam com uma licença de código aberto. **Quer participar da criação?** Sugira melhorias e edições no [Github](https://github.com/mercadopago/cart-woocommerce).

## Manutenção

Aconselhamos que você faça uma **cópia de segurança da loja on-line** antes de fazer qualquer alteração. Ao ter esta cópia pronta, exclua todos os arquivos relacionados à versão anterior do módulo. 

A seguir, execute as etapas de uma **nova instalação** para atualizar sua loja com a última versão disponível do módulo. 

---

> Mantenha o módulo sempre atualizado com a última versão. 

---

### Próximos passos

> LEFT_BUTTON_REQUIRED_ES
>
> Integrar o Mercado Pago no WooCommerce
>
> Conecte sua conta do Mercado Pago ao módulo e capture os pagamentos que você receber pelas suas vendas on-line.  
>
> 
> [Integrar](http://www.mercadopago.com.br/mlb/pt/plugins_sdks/plugins/woocommerce/integration/)

> RIGHT_BUTTON_RECOMMENDED_ES
>
> Preferências de pagamento
>
> Configure suas preferências de pagamento e faça ajustes conforme a experiência que você queira oferecer aos seus clientes.
>
> [Receber pagamentos](http://www.mercadopago.com.br/mlb/pt/plugins_sdks/plugins/woocommerce/receive-payments/)