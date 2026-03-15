# Server Metrics 2026-03-15 14:20:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 57943.9 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1785037
telemt_connections_bad_total 99212
telemt_handshake_timeouts_total 19710
telemt_upstream_connect_attempt_total 11568
telemt_upstream_connect_success_total 11519
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13488
telemt_me_reconnect_success_total 8597
telemt_me_reader_eof_total 9201
telemt_me_idle_close_by_peer_total 9201
telemt_me_route_drop_no_conn_total 610943
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1508000
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5677
telemt_desync_full_logged_total 1585
telemt_desync_suppressed_total 4092
telemt_desync_frames_bucket_total{bucket="1_2"} 1434
telemt_desync_frames_bucket_total{bucket="3_10"} 2199
telemt_desync_frames_bucket_total{bucket="gt_10"} 2044
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8887
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8586
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 1507621
telemt_user_connections_current{user="hello"} 2204
telemt_user_octets_from_client{user="hello"} 21501806540 (20.03 GB)
telemt_user_octets_to_client{user="hello"} 596514434816 (555.55 GB)
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 57944.7 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 724990
telemt_connections_bad_total 39363
telemt_handshake_timeouts_total 57595
telemt_upstream_connect_attempt_total 14796
telemt_upstream_connect_success_total 14724
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 14796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11558
telemt_me_reconnect_success_total 11467
telemt_me_reader_eof_total 12122
telemt_me_idle_close_by_peer_total 12122
telemt_me_route_drop_no_conn_total 180298
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544277
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1981
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 738
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11608
telemt_me_writer_restored_same_endpoint_total 11455
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 544531
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 7657023551 (7.13 GB)
telemt_user_octets_to_client{user="hello"} 204643877920 (190.59 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 57944.5 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1548139
telemt_connections_bad_total 45494
telemt_handshake_timeouts_total 160294
telemt_upstream_connect_attempt_total 12783
telemt_upstream_connect_success_total 12723
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 12783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11041
telemt_me_reconnect_success_total 9787
telemt_me_reader_eof_total 10377
telemt_me_idle_close_by_peer_total 10377
telemt_me_route_drop_no_conn_total 425288
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 960947
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2433
telemt_desync_full_logged_total 895
telemt_desync_suppressed_total 1538
telemt_desync_frames_bucket_total{bucket="1_2"} 559
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 942
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9956
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9768
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 957050
telemt_user_connections_current{user="hello"} 1333
telemt_user_octets_from_client{user="hello"} 13862191444 (12.91 GB)
telemt_user_octets_to_client{user="hello"} 346126240012 (322.36 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 57944.4 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 745833
telemt_connections_bad_total 71796
telemt_handshake_timeouts_total 39758
telemt_upstream_connect_attempt_total 134235
telemt_upstream_connect_success_total 133760
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 134235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 50883
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 13347
telemt_me_idle_close_by_peer_total 13347
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 170620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447063
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1173
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13126
telemt_me_refill_failed_total 1222
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1332
telemt_user_connections_total{user="hello"} 565981
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 10279933134 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 192161577337 (178.96 GB)
telemt_user_msgs_from_client{user="hello"} 2268212
telemt_user_msgs_to_client{user="hello"} 8597898
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 57945.3 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766848
telemt_connections_bad_total 9282
telemt_handshake_timeouts_total 15985
telemt_upstream_connect_attempt_total 12791
telemt_upstream_connect_success_total 12721
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13480
telemt_me_reconnect_success_total 9805
telemt_me_reader_eof_total 10491
telemt_me_idle_close_by_peer_total 10491
telemt_me_route_drop_no_conn_total 190308
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623214
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2279
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1518
telemt_desync_frames_bucket_total{bucket="1_2"} 682
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 709
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10034
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9797
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 623252
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 7776031332 (7.24 GB)
telemt_user_octets_to_client{user="hello"} 233400082212 (217.37 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 108
```