# CFd style components

## A work in progress…

We use [Tailwind](https://tailwindcss.com/docs/installation) for:

* easy, writeable utilities with a light footprint

* outsourcing the best way to manage atomic CSS (which is the best way to write CSS) to a great community of constant open-source improvement

* it feels like we write less custom code when we use it

* the config file allows us to customise many things quickly, including CSS reductions during production

Apart from Tailwind, we also rely on these component abstractions for UI patterns we constantly use. This helps us to:

* not have to resolve problems

* write even less CSS,

Because these components & utilities are abstractions on top of Tailwind, we make heavy use of it's theming capabilities with `theme(…)`.
