```mermaid
graph TD
    A[Ketua COE Hastaloka]
    B[Manajer Proyek]

    subgraph Divisi Desain
        C1[Kepala Divisi Desain]
        C2[Desainer Interior]
        C3[Asisten Desainer]
    end

    subgraph Divisi Pelaksanaan
        D1[Kepala Divisi Pelaksanaan]
        D2[Site Manager]
        D3[Supervisor Lapangan]
    end

    subgraph Divisi Keuangan dan Administrasi
        E1[Kepala Divisi Keuangan dan Administrasi]
        E2[Staff Keuangan]
        E3[Staff Administrasi]
    end

    subgraph Divisi Konsultasi
        F1[Kepala Divisi Konsultasi]
        F2[Konsultan Arsitektur]
        F3[Konsultan Interior]
    end

    A --> B
    B --> C1
    B --> D1
    B --> E1
    B --> F1

    C1 --> C2
    C1 --> C3

    D1 --> D2
    D1 --> D3

    E1 --> E2
    E1 --> E3

    F1 --> F2
    F1 --> F3

    B --> G[Dosen Supervisor]
