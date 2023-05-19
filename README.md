# shapes

Chat GPT says

| Operation | PyTorch | NumPy | Description |
|---|---|---|---|
| Reshape | `torch.reshape(tensor, shape)` | `numpy.reshape(array, newshape)` | Changes the shape of the tensor without changing its data |
| Permute | `tensor.permute(dims)` | `numpy.transpose(array, axes)` | Rearranges the dimensions of the tensor |
| Stack | `torch.stack(tensors, dim)` | `numpy.stack(arrays, axis)` | Joins a sequence of tensors along a new axis |
| Vertical Stack | `torch.vstack(tensors)` | `numpy.vstack(tuples)` | Stacks tensors in sequence vertically (row wise) |
| Horizontal Stack | `torch.hstack(tensors)` | `numpy.hstack(tuples)` | Stacks tensors in sequence horizontally (column wise) |
| Flatten | `tensor.flatten(start_dim, end_dim)` | `array.flatten()` | Reduces the tensor to one dimension |
| Transpose | `tensor.transpose(dim0, dim1)` | `numpy.transpose(array, axes)` | Swaps two dimensions of the tensor |
| Concatenate | `torch.cat(tensors, dim)` | `numpy.concatenate(arrays, axis)` | Joins a sequence of tensors along an existing axis |
| Squeeze | `tensor.squeeze(dim)` | `numpy.squeeze(array, axis)` | Removes single-dimensional entries from the shape of a tensor |
| Expand | `tensor.expand(size)` | `numpy.broadcast_to(array, shape)` | Returns a new tensor with singleton dimensions expanded to a larger size |
| Unsqueeze | `tensor.unsqueeze(dim)` | `numpy.expand_dims(array, axis)` | Adds a singleton dimension at a specific position |
| Split | `torch.split(tensor, split_size_or_sections, dim)` | `numpy.split(array, indices_or_sections, axis)` | Splits a tensor into a specific number of chunks |
| Tile | Achieved using `.repeat()` method | `numpy.tile(array, repetitions)` | Constructs an array by repeating it the number of times given by repetitions |
| Repeat | `tensor.repeat(*sizes)` | `numpy.repeat(array, repeats, axis)` | Repeats elements of an array |
| Swap axes | `tensor.permute(*dims)` | `numpy.swapaxes(array, axis1, axis2)` | Interchange two axes of an array |
| Roll | `torch.roll(input, shifts, dims=None)` | `numpy.roll(array, shift, axis=None)` | Shift elements of an array along specified axis |
| Flip | `torch.flip(input, dims)` | `numpy.flip(m, axis)` | Reverse the order of elements in an array along the given axis |
| Moveaxis | Achieved using `.permute()` method | `numpy.moveaxis(a, source, destination)` | Move axes of an array to new positions |
