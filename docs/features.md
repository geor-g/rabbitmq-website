---
title: What can RabbitMQ do for you?
displayed_sidebar: docsSidebar
---
<div id="left-content">
    <p class="intro">
        Messaging enables software applications to connect and scale. Applications can connect to each other, as components of a larger application, or to user devices and data. Messaging is asynchronous, decoupling applications by
        separating sending and receiving data.
    </p>
    <p>
        You may be thinking of data delivery, non-blocking operations or push notifications. Or you want to use publish / subscribe, asynchronous processing, or work queues. All these are patterns, and they form part of messaging.
    </p>
    <p>
        RabbitMQ is a messaging broker - an intermediary for messaging. It gives your applications a common platform to send and receive messages, and your messages a safe place to live until received.
    </p>

    <div class="docSection">
        <h2>Feature Highlights</h2>

        <h3>Reliability</h3>
        <p>
            RabbitMQ offers a variety of features to let you trade off performance with reliability, including persistence, delivery acknowledgements, publisher confirms, and high availability.
        </p>

        <h3>Flexible Routing</h3>
        <p>
            Messages are routed through exchanges before arriving at queues. RabbitMQ features several built-in exchange types for typical routing logic. For more complex routing you can
            <a href="extensions.html#routing">bind exchanges together</a> or even write your own exchange type as a plugin.
        </p>

        <h3>Clustering</h3>
        <p>Several RabbitMQ servers on a local network can be <a href="clustering.html">clustered</a> together, forming a single logical broker.</p>

        <h3>Federation</h3>
        <p>
            For servers that need to be more loosely and unreliably connected than clustering allows, RabbitMQ offers a federation model.
        </p>

        <h3>Highly Available Queues</h3>
        <p>
            RabbitMQ supports <a href="quorum-queues.html">replicated queues</a> and <a href="stream.html">streams</a>. machines in a cluster, ensuring that even in the event of hardware failure, messages are safe as long as there is a
            majority of cluster nodes online.
        </p>

        <h3>Multi-protocol</h3>
        <p>RabbitMQ supports messaging over <a href="protocols.html">a variety of messaging protocols</a>.</p>

        <h3>Many Clients</h3>
        <p>There are RabbitMQ clients for almost any <a href="devtools.html">language</a> you can think of.</p>

        <h3>Management UI</h3>
        <p>RabbitMQ ships with an easy-to use <a href="management.html">management UI</a> that allows you to monitor and control every aspect of your message broker.</p>

        <h3>Tracing</h3>
        <p>If your messaging system is misbehaving, RabbitMQ offers <a href="firehose.html">tracing</a> support to let you find out what's going on.</p>

        <h3>Plugin System</h3>
        <p>RabbitMQ ships with a variety of <a href="plugins.html">plugins</a> extending it in different ways, and you can also <a href="plugin-development.html">write your own</a>.</p>

        <h2>And Also...</h2>

        <h3>Commercial Support</h3>
        <p>Commercial <a href="services.html">support, training and consulting</a> are available from VMware.</p>

        <h3>Large Community</h3>
        <p>
            There's a large <a href="devtools.html">community</a> around RabbitMQ, producing all sorts of clients, plugins, guides, etc. Join our <a href="https://groups.google.com/forum/#!forum/rabbitmq-users">mailing list</a> to get
            involved!
        </p>
    </div>
    <div id="help-and-feedback">
        <h2>Getting Help and Providing Feedback</h2>
        <p>
            If you have questions about the contents of this guide or any other topic related to RabbitMQ, don't hesitate to ask them using <a href="https://github.com/rabbitmq/rabbitmq-server/discussions">GitHub Discussions</a> or our
            community <a href="https://rabbitmq.com/discord">Discord server</a>.
        </p>
    </div>
    <div id="contribute">
        <h2>Help Us Improve the Docs &lt;3</h2>
        <p>If you'd like to contribute an improvement to the site, its source is <a href="https://github.com/rabbitmq/rabbitmq-website">available on GitHub</a>. Simply fork the repository and submit a pull request. Thank you!</p>
    </div>
</div>
