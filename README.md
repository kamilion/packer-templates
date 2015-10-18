# Introduction

This is a set of packer templates based on ubuntu's netboot iso that spits out built images for xen.

# Configure

You might want to edit http/preseed.cfg and template.json before building an image from a template.

# Build
Change directories into the template you want to build from.
```bash
packer build template.json
```