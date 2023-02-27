# ontobot-demo
Demo for [`ontobot-change-agent`](https://github.com/hrshdhgd/ontobot-change-agent)

## Steps:
1. Create an issue with a suitable title.
2. In the description, ontobot specifically looks for the phrase: `Hey ontobot!, apply:`.
3. This is followed by commands as bullets.

For example:
```
Hey ontobot, apply:

* create broad synonym 'ABCD' for FBbt:00000016
* create exact synonym 'ABCD2' for http://purl.obolibrary.org/obo/FBbt_00000016
* create narrow synonym 'ABCD3' for http://purl.obolibrary.org/obo/FBbt_00000016
* create related synonym 'ABCD' for FBbt:00000016

```
