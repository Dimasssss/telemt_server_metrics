# Server Metrics 2026-03-12 13:54:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28519.8 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002089
telemt_connections_bad_total 10348
telemt_handshake_timeouts_total 10017
telemt_upstream_connect_attempt_total 5655
telemt_upstream_connect_success_total 5621
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 382
telemt_me_reconnect_attempts_total 8065
telemt_me_reconnect_success_total 4166
telemt_me_reader_eof_total 4453
telemt_me_idle_close_by_peer_total 4452
telemt_me_route_drop_no_conn_total 353761
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 951105
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5048
telemt_desync_full_logged_total 1275
telemt_desync_suppressed_total 3773
telemt_desync_frames_bucket_total{bucket="1_2"} 1267
telemt_desync_frames_bucket_total{bucket="3_10"} 1827
telemt_desync_frames_bucket_total{bucket="gt_10"} 1954
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4337
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4153
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 950913
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 15751121796 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 282194034572 (262.81 GB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58140.3 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479860
telemt_connections_bad_total 5324
telemt_handshake_timeouts_total 25057
telemt_upstream_connect_attempt_total 13970
telemt_upstream_connect_success_total 13963
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1125
telemt_me_reconnect_attempts_total 10940
telemt_me_reconnect_success_total 10880
telemt_me_reader_eof_total 11572
telemt_me_idle_close_by_peer_total 11572
telemt_me_route_drop_no_conn_total 138613
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425618
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1471
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 997
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 494
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10979
telemt_me_writer_restored_same_endpoint_total 10871
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 426085
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 6581339367 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 154180760782 (143.59 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 58140.2 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043595
telemt_connections_bad_total 5513
telemt_handshake_timeouts_total 76584
telemt_upstream_connect_attempt_total 13919
telemt_upstream_connect_success_total 13914
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 925
telemt_me_reconnect_attempts_total 10750
telemt_me_reconnect_success_total 10653
telemt_me_reader_eof_total 11225
telemt_me_idle_close_by_peer_total 11225
telemt_me_route_drop_no_conn_total 269333
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 742751
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3191
telemt_desync_full_logged_total 970
telemt_desync_suppressed_total 2221
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 1158
telemt_desync_frames_bucket_total{bucket="gt_10"} 1569
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10688
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10612
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 742950
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 9910309768 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 240182281361 (223.69 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 58140.8 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600950
telemt_connections_bad_total 7681
telemt_handshake_timeouts_total 55083
telemt_upstream_connect_attempt_total 15459
telemt_upstream_connect_success_total 15397
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1311
telemt_me_reconnect_attempts_total 13725
telemt_me_reconnect_success_total 12491
telemt_me_reader_eof_total 13250
telemt_me_idle_close_by_peer_total 13250
telemt_me_route_drop_no_conn_total 202133
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506921
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1025
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 665
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 312
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12626
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12470
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 506422
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 5593343012 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 205032572784 (190.95 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58140.3 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678182
telemt_connections_bad_total 1952
telemt_handshake_timeouts_total 5467
telemt_upstream_connect_attempt_total 18355
telemt_upstream_connect_success_total 18133
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 18355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 22453
telemt_me_reconnect_success_total 15226
telemt_me_reader_eof_total 15968
telemt_me_idle_close_by_peer_total 15968
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 231884
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631029
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2614
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 1738
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 917
telemt_desync_frames_bucket_total{bucket="gt_10"} 969
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 15602
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15197
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 630932
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 7253008568 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 171934685300 (160.13 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 132
```