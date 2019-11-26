- Start Date: 2019-11-26
- Target Major Version: 0.1
- Reference Issues: [#4 API](https://github.com/vuex-cloud/rfcs/issues/4)

- Implementation PR: 

# Summary

The library, beyond the fact that it's handy for the developper, is required for v-c-f (and other future libraries) to know when something changes in the store, and act fittingly on it.

# Basic example

`dispatch('module/set', { path: value })`

# Motivation

Extract the setter logic to:
- make it available to everyone without the cloud stuff
- make v-c-f a lighter library
- let other libraries be compatible with vuex-cloud-firestore

# Detailed design

Need to settle for the API

# Drawbacks



# Alternatives



# Adoption strategy

Will be usable standalone to broaden its adoption.

# Unresolved questions

