# Cell Types & Roles

## Excitatory Neurons

- **Pyramidal (E)**: Primary excitatory neurons responsible for long-range communication and local integration. Often classified by layer (e.g., L2/3, L5).

## Inhibitory Interneurons

- **PV (Parvalbumin-positive)**: Fast-spiking interneurons providing strong perisomatic inhibition. Key for gain control and E/I balance.
- **SST (Somatostatin-positive)**: Interneurons targeting the dendrites of pyramidal cells. Key for modulating top-down feedback and dendritic integration.
- **VIP (Vasoactive Intestinal Peptide-positive)**: Disinhibitory interneurons that primarily inhibit SST cells. Key for gating feedback through SST disinhibition.

## Role Assignments in Models

Every neuron in a Gamma Labyrinth model should be mapped to one of these types or a clearly defined variant, with an associated `biological_reason` for its inclusion in the omission task circuit.
