###  Usage

```golang

  // new consistent instance
	cs := consistent.NewConsistent()

  // add node with hash replicas size
	cs.Add("one", 150)
	cs.Add("two", 100)

  // get node
	node := cs.GetNode("hello")

  // remove node
  cs.Remove("one")

  // is empty
  cs.IsEmpty()
```
