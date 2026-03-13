# Server Metrics 2026-03-13 04:16:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 80269.9 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2186294
telemt_connections_bad_total 29521
telemt_handshake_timeouts_total 23145
telemt_upstream_connect_attempt_total 15887
telemt_upstream_connect_success_total 15799
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 15887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 20646
telemt_me_reconnect_success_total 11781
telemt_me_reader_eof_total 12722
telemt_me_idle_close_by_peer_total 12721
telemt_me_route_drop_no_conn_total 835573
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2010507
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8881
telemt_desync_full_logged_total 2306
telemt_desync_suppressed_total 6575
telemt_desync_frames_bucket_total{bucket="1_2"} 2337
telemt_desync_frames_bucket_total{bucket="3_10"} 3200
telemt_desync_frames_bucket_total{bucket="gt_10"} 3344
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12222
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11768
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2009936
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 29022123348 (27.03 GB)
telemt_user_octets_to_client{user="hello"} 691183210920 (643.71 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 109890.5 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889376
telemt_connections_bad_total 11856
telemt_handshake_timeouts_total 39367
telemt_upstream_connect_attempt_total 27955
telemt_upstream_connect_success_total 27925
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3474
telemt_me_reconnect_attempts_total 20905
telemt_me_reconnect_success_total 20793
telemt_me_reader_eof_total 22158
telemt_me_idle_close_by_peer_total 22158
telemt_me_route_drop_no_conn_total 284120
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 801744
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3172
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 2173
telemt_desync_frames_bucket_total{bucket="1_2"} 1274
telemt_desync_frames_bucket_total{bucket="3_10"} 1031
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20997
telemt_me_writer_restored_same_endpoint_total 20784
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 803643
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 12770414348 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 310358305691 (289.04 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 109890.3 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1837025
telemt_connections_bad_total 14502
telemt_handshake_timeouts_total 120804
telemt_upstream_connect_attempt_total 25642
telemt_upstream_connect_success_total 25632
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1629
telemt_me_reconnect_attempts_total 21061
telemt_me_reconnect_success_total 19794
telemt_me_reader_eof_total 20960
telemt_me_idle_close_by_peer_total 20959
telemt_me_route_drop_no_conn_total 594726
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1450746
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19982
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19753
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 1450356
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 25173054680 (23.44 GB)
telemt_user_octets_to_client{user="hello"} 517253499149 (481.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 109890.6 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1139662
telemt_connections_bad_total 13185
telemt_handshake_timeouts_total 74632
telemt_upstream_connect_attempt_total 37972
telemt_upstream_connect_success_total 35689
telemt_upstream_connect_fail_total 2146
telemt_upstream_connect_attempts_per_request{bucket="1"} 37698
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2145
telemt_me_keepalive_timeout_total 11381
telemt_me_reconnect_attempts_total 33272
telemt_me_reconnect_success_total 24341
telemt_me_reader_eof_total 26269
telemt_me_idle_close_by_peer_total 26262
telemt_me_route_drop_no_conn_total 405045
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 979597
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1940
telemt_desync_full_logged_total 641
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 758
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 24780
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24317
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 984775
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 15106495413 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 387646296662 (361.02 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 109890.4 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1265207
telemt_connections_bad_total 12877
telemt_handshake_timeouts_total 10156
telemt_upstream_connect_attempt_total 34757
telemt_upstream_connect_success_total 34334
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 34757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_keepalive_timeout_total 1922
telemt_me_reconnect_attempts_total 42594
telemt_me_reconnect_success_total 28862
telemt_me_reader_eof_total 30332
telemt_me_idle_close_by_peer_total 30332
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 469874
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1170133
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4296
telemt_desync_full_logged_total 1539
telemt_desync_suppressed_total 2757
telemt_desync_frames_bucket_total{bucket="1_2"} 1299
telemt_desync_frames_bucket_total{bucket="3_10"} 1405
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 29621
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28812
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 1169987
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 14322007872 (13.34 GB)
telemt_user_octets_to_client{user="hello"} 400983277532 (373.44 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 58
```