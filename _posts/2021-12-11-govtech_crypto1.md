---
title: 'Can COViD Steal Bob’s Idea?'
date: 2020-12-11 00:00:00+0800
excerpt: Can CoViD Steal Bob's Idea is the first Crypto challenge of GovTech Stack The Flags 2020. This challenge requires us to examine a .pcap file to retrieve information about a Diffie-Hellman Key Exchange.
comments: false
---
## Introduction
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus pretium est neque, a semper ex dapibus ullamcorper. Donec nec metus vitae lectus consectetur malesuada at sed leo. Vivamus ornare augue at metus convallis, vel pulvinar risus pellentesque. In hac habitasse platea dictumst. Ut in tellus neque. Ut gravida nisl ullamcorper ligula facilisis, non molestie dolor bibendum. Aliquam posuere vulputate sapien, in dictum elit condimentum.

## Basic analysis
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus pretium est neque, a semper ex dapibus ullamcorper. Donec nec metus vitae lectus consectetur malesuada at sed leo. Vivamus ornare augue at metus convallis, vel pulvinar risus pellentesque. In hac habitasse platea dictumst. Ut in tellus neque. Ut gravida nisl ullamcorper ligula facilisis, non molestie dolor bibendum. Aliquam posuere vulputate sapien, in dictum elit condimentum.

## Exploitation
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus pretium est neque, a semper ex dapibus ullamcorper. Donec nec metus vitae lectus consectetur malesuada at sed leo. Vivamus ornare augue at metus convallis, vel pulvinar risus pellentesque. In hac habitasse platea dictumst. Ut in tellus neque. Ut gravida nisl ullamcorper ligula facilisis, non molestie dolor bibendum. Aliquam posuere vulputate sapien, in dictum elit condimentum.

```javascript
var fakearr_data = [h2f(0x08241909, 0x080406e9), 0.1, 0.2]; // 0x08241909 and 0x080406e9 are two static values at the start of every floating pointer array
var loc = deref(fakearr_data, 0);
console.log(loc.toString(16));
fakearr_data[1] = h2f(loc + 0x18, 0x80000); // 0x80000 is right shifted once; 0x40000 element array
fakearr_data[2] = h2f(0x08040a3d, 0x80000); // 0x08040a3d is header of contents of an array
```

## Conclusion
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus pretium est neque, a semper ex dapibus ullamcorper. Donec nec metus vitae lectus consectetur malesuada at sed leo. Vivamus ornare augue at metus convallis, vel pulvinar risus pellentesque. In hac habitasse platea dictumst. Ut in tellus neque. Ut gravida nisl ullamcorper ligula facilisis, non molestie dolor bibendum. Aliquam posuere vulputate sapien, in dictum elit condimentum.