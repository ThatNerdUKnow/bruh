## bruh_moment
Re-export of the fabulous error crate, `anyhow`

# Usage
```rs
return Err(bruh!("Missing attribute: {}", missing));
```
or 
```rs
pub fn fallible_function()->Result<_,Bruh>
```

# Why?
I remembered that `yeet` was added to nightly rust so I thought that `Bruh` would be a funny name for an error type