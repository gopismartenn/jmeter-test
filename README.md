# jmeter-test
node {
  stage 'Run JMeter Test'
  sh '/home/ubuntu/apache-jmeter-3.1/bin/jmeter.sh -n -t /home/ubuntu/Jenkins_demo1.jmx -l test.jtl'
}
