
  git config --global credential.helper 'cache --timeout=7200'
  printf "protocol=https\nhost=github.com\nusername=x-access-token\npassword=%s\n\n" "$GHT" | git credential approve
  unset GHT
  bench switch-to-branch version-15 iftas_customization iftas_finance rfp --upgrade


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
