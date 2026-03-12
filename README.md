# Server Metrics 2026-03-12 14:04:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29130.9 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1029107
telemt_connections_bad_total 10454
telemt_handshake_timeouts_total 10685
telemt_upstream_connect_attempt_total 5799
telemt_upstream_connect_success_total 5765
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 387
telemt_me_reconnect_attempts_total 8166
telemt_me_reconnect_success_total 4267
telemt_me_reader_eof_total 4566
telemt_me_idle_close_by_peer_total 4565
telemt_me_route_drop_no_conn_total 364362
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975743
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5213
telemt_desync_full_logged_total 1318
telemt_desync_suppressed_total 3895
telemt_desync_frames_bucket_total{bucket="1_2"} 1301
telemt_desync_frames_bucket_total{bucket="3_10"} 1895
telemt_desync_frames_bucket_total{bucket="gt_10"} 2017
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4440
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4254
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 975503
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 15978863032 (14.88 GB)
telemt_user_octets_to_client{user="hello"} 287180657208 (267.46 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58751.2 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488349
telemt_connections_bad_total 5333
telemt_handshake_timeouts_total 25362
telemt_upstream_connect_attempt_total 14101
telemt_upstream_connect_success_total 14094
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1126
telemt_me_reconnect_attempts_total 11028
telemt_me_reconnect_success_total 10966
telemt_me_reader_eof_total 11667
telemt_me_idle_close_by_peer_total 11667
telemt_me_route_drop_no_conn_total 141413
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1534
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 1044
telemt_desync_frames_bucket_total{bucket="1_2"} 649
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11068
telemt_me_writer_restored_same_endpoint_total 10957
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 434056
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 6703319287 (6.24 GB)
telemt_user_octets_to_client{user="hello"} 156231747474 (145.50 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 58751.2 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059328
telemt_connections_bad_total 5555
telemt_handshake_timeouts_total 77531
telemt_upstream_connect_attempt_total 14061
telemt_upstream_connect_success_total 14056
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 927
telemt_me_reconnect_attempts_total 10848
telemt_me_reconnect_success_total 10750
telemt_me_reader_eof_total 11326
telemt_me_idle_close_by_peer_total 11326
telemt_me_route_drop_no_conn_total 274438
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 756526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3237
telemt_desync_full_logged_total 987
telemt_desync_suppressed_total 2250
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1596
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10789
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10709
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 756724
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 10040444040 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 243626540809 (226.89 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 58751.4 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 611840
telemt_connections_bad_total 7682
telemt_handshake_timeouts_total 55302
telemt_upstream_connect_attempt_total 15602
telemt_upstream_connect_success_total 15540
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1312
telemt_me_reconnect_attempts_total 13824
telemt_me_reconnect_success_total 12590
telemt_me_reader_eof_total 13359
telemt_me_idle_close_by_peer_total 13359
telemt_me_route_drop_no_conn_total 205709
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517373
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1044
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12725
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12569
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 516876
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 5700321072 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 209473419516 (195.09 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58751.5 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691332
telemt_connections_bad_total 3113
telemt_handshake_timeouts_total 5542
telemt_upstream_connect_attempt_total 18504
telemt_upstream_connect_success_total 18278
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 18504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 22553
telemt_me_reconnect_success_total 15325
telemt_me_reader_eof_total 16070
telemt_me_idle_close_by_peer_total 16070
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 237092
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642375
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2635
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1749
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 923
telemt_desync_frames_bucket_total{bucket="gt_10"} 977
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 15705
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15294
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 642278
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 7410200752 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 175546756136 (163.49 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 139
```