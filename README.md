# FormIOBundle
FormIO functionality for [common gateway](https://github.com/ConductionNL/commonground-gateway)


### Using this bundle
U can install this plugin by installing with command:
`composer require common-gateway/formio-bundle:dev-main`
in the directory where your composer.json lives.


In the common gateway, if you want to use your code when triggered by an event with a action, make sure the class of the action object is set as the handler name including the namespace. For example if I want to use the FormIOService I can set the FormIOHandler as `CommonGateway\FormIOBundle\ActionHandler\FormIOHandler`.
