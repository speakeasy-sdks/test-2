<!-- Start SDK Example Usage [usage] -->
```go
package main

import (
	"context"
	test2 "github.com/speakeasy-sdks/test-2"
	"log"
)

func main() {
	s := test2.New()

	ctx := context.Background()
	res, err := s.Pets.CreatePets(ctx)
	if err != nil {
		log.Fatal(err)
	}
	if res != nil {
		// handle response
	}
}

```
<!-- End SDK Example Usage [usage] -->