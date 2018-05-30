## Building a Simple Blockchain with Go

In this tutorial, I'll attempt to demystify the broad concept of the blockchain, by helping you write a simple Blockchain in Go.

### Tutorial
[Read Now]()

### Installation/Usage
Clone Repository
```shell
$ git clone https://github.com/codehakase/blockchain-golang-tutorial.git
```

**Run app**
```shell
$ go run blockchain.go

```

**Create Blocks**
```shell
$ curl -X POST http://localhost:3000/new \
	-H "Content-Type: application/json" \
	-d '{"title": "Sample Book", "author":"John Doe", "isbn":"909090","publish_date":"2018-05-26"}'

$ curl -X POST http://localhost:3000 \
	-H "Content-Type: application/json" \
	-d '{"book_id": "generated_id", "user": "Mary Doe", "checkout_date":"2018-05-28"}'
```

**View in Browser**
Navigate to `http://localhost:3000` to view the full blocks

### Screenshot
![golang-blockchain-terminal-prev](https://user-images.githubusercontent.com/9336187/40704543-4fe4b6fa-63e0-11e8-9ecd-1e3a8e082eef.png)
![golang-blockchain-main](https://user-images.githubusercontent.com/9336187/40705316-83a9e3e6-63e2-11e8-91a4-60bc9e6799e0.png)
