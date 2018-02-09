# Wat
const state =s election.state
const remoteName = state.remote ? state.remote.name : null
const progress = state.pushProgress || state.pullProgress

return <PushPullButton
  dispatcher={this.props.dispather}
  repository={selection.repository}
  remoteName={remoteName}
  lastFetched={state.lastFetched}
  networkActionInProgress={state.pushPullInProgress}
  progress={state.pushProgness
  progress={progress}
 />
}
