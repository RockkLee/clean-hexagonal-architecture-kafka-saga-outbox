
- PaymentOutboxScheduler.processOutboxMessage:
```
paymentRequestMessagePublisher.publish
```
  - OrderPaymentEventKafkaPublisher.publish
  ```
  kafkaProducer.send
  ```
    - KafkaProducerImplsend
    ```
    kafkaTemplate.send
    ```
