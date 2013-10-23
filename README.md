# RabbitMQ Visualizer
A representation of the RabbitMQ messaging concepts visualized using D3.js
## Usage
The live version can be found here http://jmcle.github.io/rabbitmq-visualizer
## Dependencies
* Libraries
 * D3.js
 * jQuery 1.10+
 * Bootstrap 3
* Browsers
 * Best experienced using Chrome
 * Mostly working in IE 9+ and Firefox 24

## Features
* Exchange types (direct, fanout, exchange)
* Queues and message queuing
* Producers and consumers
* Binding creation
* Binding keys and sending messages with routing keys
* Round robin consumer behavior
* Resource renaming
* Import/Export (compatible with RabbitMQ Simulator exports)
* Predefined examples to choose from

## Why
I created this project both as a way to learn D3.js and to create a more portable and customizable version of the RabbitMQ Simulator. I needed a way to better embed RabbitMQ visualizations into presentations and wanted something without a server side component.

This implementation can be completely self contained and customized by users without the need to setup a server to host the project.

## Todo
* Automated interval based message delivery
* Customizable message payload and routing key
* Support for importing RabbitMQ broker exports
* Add unique shapes for each resource type
* Display log of received messages
* Better IE support
* Customization options (colors, layouts, etc)

## Contact
* Twitter: [@defactojames](http://www.twitter.com/defactojames)
