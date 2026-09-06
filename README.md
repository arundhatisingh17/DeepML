# DeepML

Solutions to problems from [deep-ml.com](https://www.deep-ml.com), written from scratch.

The point is to implement the mechanics rather than call a library. Writing a dot product or a
transpose by hand forces you to be explicit about things `numpy` normally hides, like which index
is shared between two operands and what the output shape has to be.

I'm doing these while working through a Master's, partly to build that intuition and partly as
prep for ML interviews, where getting asked to derive or implement something without a library is
common.

## Layout

One file per problem, named after the function it defines. Solutions are kept as submitted, so the
style varies as I go.

## Running

Plain Python 3.10+. No dependencies.

```bash
python -c "from matrix_dot_vector import matrix_dot_vector; print(matrix_dot_vector([[1,2],[3,4]], [1,2]))"
```
