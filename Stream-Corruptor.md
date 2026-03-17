# Eyevinn Chaos Stream Proxy

The Eyevinn Chaos Stream Proxy is an open source tool for testing how video players and streaming services behave under degraded network conditions. It acts as a proxy between the streaming application and the origin, applying configurable corruptions and faults to MPEG-DASH and HLS manifests and segment requests on the fly.

## Use cases

- Test how a video player recovers from in-stream failures
- Verify that QoE analytics correctly report stream errors
- Simulate CDN or network issues in a controlled environment

## Getting started

The tool is freely available as open source software:

- **GitHub**: [https://github.com/Eyevinn/chaos-stream-proxy](https://github.com/Eyevinn/chaos-stream-proxy)
- **Open Source Cloud**: [https://app.osaas.io/dashboard/service/eyevinn-chaos-stream-proxy](https://app.osaas.io/dashboard/service/eyevinn-chaos-stream-proxy)

You can run it locally from source or deploy it instantly via the Open Source Cloud platform.

## Further reading

- [Testing your Video Player with Bad Streams](https://medium.com/@eyevinntechnology/testing-your-video-player-with-bad-streams-c70cac51deab)
- [Delivering flawless streams, regardless of the challenges in network conditions](https://medium.com/@eyevinntechnology/delivering-flawless-streams-regardless-of-the-challenges-in-network-conditions-e466bad5b83f)
