# DOP303 - Construyendo la siguiente generación de aplicaciones serverless con arquitecturas orientadas a eventos, con CrowdFarming

>&nbsp;
> Las arquitecturas orientadas a eventos permiten construir aplicaciones distribuidas que son altamente disponibles. En esta sesión, cubriremos diferentes patrones para conectar microservicios y coordinar tareas sin apenas código. Contaremos con la experiencia de CrowdFarming, una plataforma que pone alimentos ecológicos al alcance de los consumidores finales. Profundizaremos en su uso de servicios como Amazon EventBridge y AWS Step Functions para gestionar decenas de miles de pedidos al mes de forma asíncrona y serverless.
> - Alberto Gil - Subscriptions Domain Expert, CrowdFarming
>  - Moisés Calviño - CoFounder & CTO, CrowdFarming
>  - Jesús Bernal - Startup Solutions Architect, AWS
>&nbsp;

Listado de recursos de la sesión DOP303, como parte del track de _Tecnologías de Desarrollo_ en el [AWS Summit Madrid 2024](https://aws.amazon.com/es/events/summits/emea/madrid/).

## Event-driven architectures

- [Introducción a las arquitecturas orientadas a eventos](https://serverlessland.com/event-driven-architecture)

### Initial Design: Understand behaviour, then implemenation

- [Ubiquitous Language](https://martinfowler.com/bliki/UbiquitousLanguage.html)
- [EventStorming](https://eda-visuals.boyney.io/visuals/event-storming)

### Messaging and Integration patterns

- [EDA Visuals](https://serverlessland.com/event-driven-architecture/visuals): _Small bite sized visuals about event-driven architectures_. Tarjetas visuales que exploran desde conceptos básicos de EDA hasta patrones de mensajería e integración pasando por domain-driven design, etc.
- [Colección de patrones](https://serverlessland.com/patterns) para tener un punto de partida mediante IaC al construir tus aplicaciones y/o integraciones.
- [Amazon SQS](https://serverlessland.com/sqs)
- [Amazon EventBridge](https://serverlessland.com/eventbridge)
- [AWS Step Functions](https://serverlessland.com/step-functions)

### Operation and maintenace

- [EventBridge Schema Registry](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-schema.html)
- [AsyncAPI](https://www.asyncapi.com/en)
- [EventCatalog](https://www.eventcatalog.dev/)

## Recap and next steps

- Continua tu aprendizaje de serverless y arquitecturas orientadas a eventos mediante los [Learning Paths oficiales](https://serverlessland.com/learning-serverless).

## Additional resources

- Customer success story:
  - [AWS Blog | Event Driven Architecture using Amazon EventBridge – Part 1](https://aws.amazon.com/blogs/mt/event-driven-architecture-using-amazon-eventbridge/)
- Workshops
  - [Building event-driven architectures on AWS](https://catalog.workshops.aws/building-event-driven-architectures-on-aws/en-US)
  - [Serverlesspresso](https://catalog.us-east-1.prod.workshops.aws/workshops/28e7066a-b0bb-42ad-a0e9-8e8eeeb51133/en-US)

¡Gracias!