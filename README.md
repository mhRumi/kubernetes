# Kubernetes

**Kubernetes কী?**

Kubernetes হচ্ছে কন্টেইনার ম্যানেজমেন্ট টুল বা কন্টেইনার orchestration ইঞ্জিন।
কন্টেইনার ম্যানেজমেন্ট টুল এর কাজ হচ্ছে  containerized applicatoin গুলোকে ম্যানেজ করা, deployment অটোমেটেড করা , স্কেলিং করা (প্রয়োজন অনুযায়ী applicatoin এর রেপলিকা তৈরি করা),Load balancing করা ইত্যাদি ।
বহুল ব্যবহৃত কয়েকটি কন্টেইনার ম্যানেজমেন্ট টুল হচ্ছেঃ 

<ol>
  <ul> Kubernets </ul> 
  <ul> Docker Swarm </ul>
  <ul> Apache Mesos Marathon </ul>
</ol>
 
**Containerized applicatoin কী?**

কোন application রান করার জন্য যেসব tool, application, environment প্রয়োজন সবকিছু একসাথে encapsulate করাই হচ্ছে containerization, যে application এর সমস্ত dependency & environment একসাথে encapsulate করা হয় সেটিই হচ্ছে Containerized applicatoin. আমরা অনেক সময়ই এমন পরিস্থিতি পড়ে যাই , একটি আপ্লিকেশন আমাদের নিজের ডিভাইসে রান হচ্ছে কিন্তু অন্য ডিভাইসে রান হচ্ছে না ,যেহেতু containerization এর মাধ্যমে আমরা একটি আপ্লিকেশনের সকল ডিপেন্ডেন্সি এবং এনভাইরনমেন্ট একসাথে encapsulate করি,containerized application এর ক্ষেত্রে আমাদের এমন সমস্যায় পরতে হয় না, আমাদের application যেকোনো সিস্টেমে রান করার জন্য প্রস্তুত । 
