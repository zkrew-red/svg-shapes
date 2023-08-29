<script>
  import HiImage from "./../assets/hi.png";
  import XIcon from "./../assets/x-icon.svg";
  import ArrowUpIcon from "./../assets/arrow-up.svg";
  import GlobeIcon from "./../assets/globe-icon.svg";
  import GithubLogo from "./../assets/github.svg";

  let display = true;

  const toggleDisplay = () => {
    display = !display;
  };
</script>

<style>
  .callout {
    display: none;
  }

  @media (min-width: 768px) {
    .callout {
      display: block;
    }
  }

  .callout {
    position: absolute;
    color: black;
    bottom: 16px;
    left: 16px;
    z-index: 50;
    box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.2);
    border-radius: 0.375rem;
    background-color: #fff;
    max-width: 20rem;
    word-break: break-all;
    font-weight: 300;
  }

  button {
    background: none;
    outline: none;
    border: none;
    cursor: pointer;
  }

  .callout button {
    float: right;
    margin-top: 1rem;
    margin-right: 1rem;
  }

  .callout .content {
    padding: 1rem;
  }

  .callout .content .greeting {
    margin-top: 1rem;
    font-size: 1.25rem;
  }

  .callout .content .urgency {
    margin-top: 1rem;
    font-size: 1.125rem;
  }

  .callout .content .actions {
    display: flex;
    margin-top: 2rem;
    gap: 1rem;
    align-items: center;
  }

  .callout .content .actions .contact-btn {
    padding: 0.5rem 1rem;
    background-color: #000;
    border-radius: 0.375rem;
    color: #fff;
  }

  .callout .content .actions .portfolio-link .globe-icon {
    width: 1.5rem;
    height: 1.5rem;
  }

  .callout .content .actions .github-link {
    fill: currentColor;
  }

  .callout .hi-image {
    width: 5rem;
    margin-right: 2rem;
    margin-bottom: -6px;
  }
</style>
