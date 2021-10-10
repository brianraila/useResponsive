# useResponsive
React useResponsive Hook

## Usage

`const displaySize = useResponsive();`

Using it to determine what to return:

`if (displaySize < DisplaySize.MobileS) {
  return <div>Size not supported</div>;
}`

Using it directly in JSX:
`<div>
  { displaySize >= DisplaySize.MobileM
    ? <div>BIG TEXT!</div>
    : <div>small text :( </div>
  }
</div>`
