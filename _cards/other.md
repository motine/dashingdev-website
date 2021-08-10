---
title: Other Card
type: pattern
summary: "**Other Cards** Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor."
---

TODO add image!

**useful** to encapsulate knowledge which classes belong together.

**provide** an interchangeable factory object and delegate the creation of objects to it.

**example**

```
current_os.gui_factory.create_button()
```

+	allows to add or change a whole set of classes w/o changing the using code
+	makes it possible to configure concrete implementations at runtime
+	provides guidance which objects are compatible for use together
+	improves testability by allowing to inject mock objects
-	may make it harder to debug because of additional classes 