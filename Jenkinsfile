

pipelineJob('First') {
  definition {
    cpsScm {
      scm {
        git {
          remote {
            url('https://github.com/manusmtp/dslmanu.git')
          }
          branch('*/master')
        }
      }
      lightweight()
    }
  }
}