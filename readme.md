# GraphQL server

### graphql을 연습하고 싶다면??

`https://graphql.org/swapi-graphql`

### Data를 serving해주기 위해서는

server를 통해 data를 serving해주기 위해서는 serving해주고자 하는 data의 type 정보를 알아야 한다.
이럴 때는

```
type Query {
    text: String
    hello: String
}
```

이렇게 `type Query` 안에 넣어준다.

### graphql에서의 type

GET request에 해당하는 것들은 `type Query`안에
GET request를 제외하고 나머지 것들은 `type Mutation`안에 넣어준다.
