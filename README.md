<div align="center">
<h1 align="center">
        Awesome Queues
</h1>

<a href="https://github.com/sindresorhus/awesome">
        <img src="https://awesome.re/badge-flat.svg" alt="Awesome">
</a>

<p class="center">
        A curated list of awesome queueing systems for background jobs and distributed tasks.
</p>
</div>

<br />
<br />


Queues allow you to create reliable distributed background tasks - logic that runs in the background, separate from your main request.

<br />
<hr />
<br />

### Serverless queues

- [Inngest](https://github.com/inngest/inngest-cli) - An event-driven serverless queue, in which serverless functions are triggered by HTTP events.
- [SQS](https://aws.amazon.com/sqs/) - A cloud message queue from AWS, supporting Lambda functions

### Language-agnostic queues

- [SQS](https://aws.amazon.com/sqs/) - A cloud message queue from AWS.  Supports elastic scale, and delaying jobs up to 15m ahead of time.
- [Inngest](https://github.com/inngest/inngest-cli) - An event-driven queue, running serverless functions in any language
- [Faktory](https://github.com/contribsys/faktory) - A self-hosted distributed task queue written in Go, with SDKs available for many languages

### Language-specific queues

#### Python queues

- [Celery](https://github.com/celery/celery), a commonly used distributed task queue written in Python
- [RQ](https://github.com/rq/rq), a simple task queue for Python backed by Redis

#### Go queues

- [Tasqueue](https://github.com/kalbhor/Tasqueue) - A task queue service backed by Redis or NATS.

#### Ruby queues

- [Sidekiq](https://github.com/mperham/sidekiq) - A very common background task runner for Ruby, backed by Redis.  It supports cron, but not delayed jobs.

#### JavaScript, TypeScript, and NodeJS queues

- [BullMQ](https://github.com/taskforcesh/bullmq) - A message queue for NodeJS backed by redis
