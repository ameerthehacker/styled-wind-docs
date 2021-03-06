![Styled-wind](./logo.svg)

> A magical implementation of tailwind-like classnames into styled-components.

## What is styled wind?

Styled-wind is a CSS-in-JS library, written on top of styled-components. It inherits everything from styled-components and also gives you the flexibility to use tailwind classnames along with styled-components.

## Motivation

Styled-components is one of the most famous CSS-in-JSS library and has been favorite styling tool in the React ecosystem. On the other hand, tailwind css has gained a lot of momentum recently because of the ease of use and quick development of responsive web apps. However, there are few practical issues in using tailwind css. This library is an attempt to get the best of both worlds.

See the [Quick start](quickstart.md) guide for more details.

## Why styled-wind?

- Building Responsive sites becomes a lot easier
- Very small bundle size to use in existing projects
- 2 minutes migration to use tailwind in a styled-component project
- Solving the readability issues of tailwind
- Build reusable components / UI libraries
- Dynamic styling using props
- Benefits of tailwind in Component world of React & Styled-components
- Remembering or writing CSS is not required
- Tailwind like development for React Native

## Prerequisite

Basic knowledge of [styled-components](https://styled-components.com/) and [tailwindcss](https://tailwindcss.com/). The list of tailwind class names can be found [here](https://nerdcave.com/tailwind-cheat-sheet)


## Features

- Zero-CSS
- Responsive
- Custom Styling/Theme
- No class name bugs
- Development speed
- Automatic critical CSS
- Easier maintenance of CSS
- Automatic vendor prefixing
- Simple dynamic styling
- Tailwind is not required


## Roadmap/TODO:

> Contributions & Suggestions welcome 

- Auto intellisense, syntax highlighting and linting
- Support for React Native
- Allowing tailwind classes inside prop's conditions
- CLI/Context for consuming custom styling
- Add support for animation classes
- Optimize the library

## Caveats

- React Native support is not added yet
- Tailwind classnames aren't supported yet inside keyframes and expressions. However you may still use regular CSS for expressions & keyframes
    ```sh
    // Not allowed. Will be implemented in future
        const StyledComponent = styled.div`
            @keyframes mymove{
                from { .top-10 }
                to { .top-16 }
            }
        `

        // Allowed
        const StyledComponent = styled.div`
            @keyframes mymove {
                from {top: 0px;}
                to {top: 200px;}
            }
        `
    ```
- Animation classes aren't supported yet.
- Custom theme can currently be configured only inside `index.html` file
- No support for variants as we find no dominant use case in component world
- Please report if you happen to find any issues.

## Examples
<!-- Add code sandbox like: TODO -->
Check out the [CodeSandBox](https://github.com/docsifyjs/awesome-docsify#showcase) to see styled-wind in use.

## Community

The creators of the library are always open to discussions/suggestions. Their twitter accounts:

- Ameer Jhan [Twitter](https://twitter.com/ameerthehacker)
- Vilva Athiban [Twitter](https://twitter.com/vilvaathibanpb)
