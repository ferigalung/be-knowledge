### Kubernetes
Tools _Orkestrasi_ yang digunakan untuk mengatur dan mengelola containers aplikasi berskala besar. Bisa untuk mengatur deployment, scaling, dll.

Fitur utama kubernetes:
- Pod: unit terkecil di kubernetes, berupa 1 atau lebih container (biasanya container docker)
- Service: kumpulan pod yang dapat diakses antar cluster atau untuk ekspos ke luar
- Namespace: Fitur untuk mengelola resource di cluster, berguna jika terdapat beberapa project/team/organisasi dalam 1 cluster
- Deployment: Ngelola update aplikasi tanpa downtime. Jadi bisa rollout versi baru, rollback ke versi lama, dll.
- Volume: Ngelola storage yang bisa dipakai container dalam Pod.

Kubernetes biasanya dipake berbarengan dengan jenkins untuk menghandle pipeline CI/CD, ada alternatif tools lain untuk CI/CD namun jenkins yang paling populer.

Kubernetes adalah tools open-source dan free, namun ada kubernetes-based system yang berbayar dan ditargetkan untuk enterprise, memiliki fitur lebih jika merasa kubernetes masih belum memenuhi kebutuhan, tools itu bernama **Openshift**