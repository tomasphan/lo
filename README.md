[![Build Status](https://travis-ci.org/apex-lodash/lo.svg?branch=master)](https://travis-ci.org/apex-lodash/lo)

#apex-lodash
This class provides some similar utility methods to that of [lodash](https://lodash.com/).

#Installation
TODO: Add installation guide

#Usage
##Pluck
Used to pluck a list of fields out of a list of objects

###Single object
```java
Account account = ...;
Object lo.pluck(account, 'name');
```

###Single depth
```java
List<Account> accountList = ...;
List<Object> lo.pluck(accountList, 'name');
```

###Multiple depths
```java
List<Case> caseList = ...;
List<Object> lo.pluck(caseList, 'contact.account.name');
```