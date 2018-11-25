# JCON: JSON for Configuration 

JCON is a configuration format that keeps the familiarity of JSON, but requires less syntax -- making it easier to read and write.

## At a Glance

```

{
    // this is a comment
    myKey: {

        key: this is a string
        boolean: true
        number: 123

        list: [
            this is item 1
            this is item 2
        ]
        
        multiline: `
            This is a
            multiline
            string
        `
    }
}


```
