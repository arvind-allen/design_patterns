# Builder design pattern

Some objects are simple and can be created in a single constructor call

Other objects require a lot of ceremony to create 

Having a factory function with 10 arguments is not productive 

Instead, opt for piecewise (piece-by-piece) construction

### Builder provides an API for constructing an object step-by-step