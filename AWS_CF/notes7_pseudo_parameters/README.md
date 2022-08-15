#Pseudo Parameters


---> Pseudo Parameters as pre-defined by AWS CF and enabled by default

---> We can reference them by using Ref/Sub function (As we use to refer parameter)

List of pseudo parameters:
```
---> AWS::AccountId ----- Returns AccountId (eg- 1212121212)


---> AWS::NotificationARNs ---- Returns the list of notification Amazon Resource Names(ARNs) for the current stack (Eg- [arn:aws:sns:us-east-1:1212121212:Topic])


---> AWS::NoValue ---- Does not return a value


---> AWS::Partition ---- Returns the partition that the resource is in (Eg- aws)


---> AWS::Region ----  Returns region name (eg - us-east-1)


---> AWS::StackId ---- Returns CF stack if (Eg- arn:aws:cloudformation:us-east-2:1212121212:stack/tstack/51af3dc0-da77-11e4-872e-1234567db1230)


---> AWS::StackName ---- Returns the Stack Name (Eg : MyStack)


---> AWS::URLSuffix ---- Returns suffix for a domain/URL ( Eg: amazonaws.com)


