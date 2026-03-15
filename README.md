# Server Metrics 2026-03-15 12:22:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 50893.2 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1421649
telemt_connections_bad_total 83318
telemt_handshake_timeouts_total 11927
telemt_upstream_connect_attempt_total 10182
telemt_upstream_connect_success_total 10134
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12456
telemt_me_reconnect_success_total 7578
telemt_me_reader_eof_total 8133
telemt_me_idle_close_by_peer_total 8133
telemt_me_route_drop_no_conn_total 475232
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1192204
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4509
telemt_desync_full_logged_total 1275
telemt_desync_suppressed_total 3234
telemt_desync_frames_bucket_total{bucket="1_2"} 1100
telemt_desync_frames_bucket_total{bucket="3_10"} 1771
telemt_desync_frames_bucket_total{bucket="gt_10"} 1638
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7843
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7567
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 1191886
telemt_user_connections_current{user="hello"} 2216
telemt_user_octets_from_client{user="hello"} 16897901412 (15.74 GB)
telemt_user_octets_to_client{user="hello"} 478219955432 (445.38 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 50893.9 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565337
telemt_connections_bad_total 29044
telemt_handshake_timeouts_total 34368
telemt_upstream_connect_attempt_total 13242
telemt_upstream_connect_success_total 13177
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10365
telemt_me_reconnect_success_total 10292
telemt_me_reader_eof_total 10885
telemt_me_idle_close_by_peer_total 10885
telemt_me_route_drop_no_conn_total 143722
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439760
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1723
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1121
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10405
telemt_me_writer_restored_same_endpoint_total 10280
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 440028
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 6228408195 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 162578906740 (151.41 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 50893.9 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131977
telemt_connections_bad_total 36956
telemt_handshake_timeouts_total 114173
telemt_upstream_connect_attempt_total 11263
telemt_upstream_connect_success_total 11209
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 11263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 9884
telemt_me_reconnect_success_total 8640
telemt_me_reader_eof_total 9162
telemt_me_idle_close_by_peer_total 9162
telemt_me_route_drop_no_conn_total 349163
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 764438
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1972
telemt_desync_full_logged_total 699
telemt_desync_suppressed_total 1273
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8790
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8621
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 760953
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 11204996328 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 287024523908 (267.31 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 50893.8 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565467
telemt_connections_bad_total 65673
telemt_handshake_timeouts_total 32721
telemt_upstream_connect_attempt_total 14592
telemt_upstream_connect_success_total 14214
telemt_upstream_connect_fail_total 378
telemt_upstream_connect_attempts_per_request{bucket="1"} 14592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 378
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 39754
telemt_me_reconnect_success_total 11660
telemt_me_reader_eof_total 12872
telemt_me_idle_close_by_peer_total 12872
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 160284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422255
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1097
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12648
telemt_me_refill_failed_total 878
telemt_me_writer_restored_same_endpoint_total 11628
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 988
telemt_user_connections_total{user="hello"} 422127
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 7386153864 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 145632459640 (135.63 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 50895.0 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609392
telemt_connections_bad_total 6907
telemt_handshake_timeouts_total 13053
telemt_upstream_connect_attempt_total 11364
telemt_upstream_connect_success_total 11306
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 8801
telemt_me_reconnect_success_total 8751
telemt_me_reader_eof_total 9280
telemt_me_idle_close_by_peer_total 9280
telemt_me_route_drop_no_conn_total 152237
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493589
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1936
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1301
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 767
telemt_desync_frames_bucket_total{bucket="gt_10"} 604
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8851
telemt_me_writer_restored_same_endpoint_total 8743
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 493622
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 6415848500 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 177418120024 (165.23 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 110
```