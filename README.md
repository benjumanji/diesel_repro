# diesel_repro

This shows that diesel_migrations is doing something that the regular diesel crate doesn't when it comes to cross compilation.

If you are on linux just run ./run-nowork and ./run-works to see a project compile or fail to compile depending on whether just regular diesel is used vs diesel migrations. If you are on a mac you will need to make sure that `works` and `nowork` are availble for bind mounting.
