
# Change Log

## Version 1.3.0 (21.03.2019)

New manual proxied methods:
- splice
- to_asci_lowercase
- to_asci_upercase

New Into impl for following types:
- Rc<[T]>
- Arc<[T]>
- Box<[T]>
- VecDeque<T>

### Unstable/Nightly features

New TryFrom impl for follwing types:
- Box<[T]>
- BinaryHeap<T>
- VecDeque<T>
- String
- &str
- &[T] where T: Clone
- &mut [T] where T: Clone

## Version 1.2.0 (20.03.2019)

- Added new `try_from_vec` which returns a `Result<Vec1<T>, Size0Error>`.
- Deprecated `from_vec` as it doesn't return a error type as error.

### Unstable/Nightly features

- New `unstable-nightly-try-from-impl` feature which adds a `TryFrom<Vec<T>>` implementation.


## Version 1.1.0

- Addead a `serde` feature implementing `Serialize`/`Deserialize`.
