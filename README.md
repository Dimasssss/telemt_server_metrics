# Server Metrics 2026-03-13 16:11:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 123194.0 (34h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3877639
telemt_connections_bad_total 37438
telemt_handshake_timeouts_total 90640
telemt_upstream_connect_attempt_total 23884
telemt_upstream_connect_success_total 23747
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2218
telemt_me_reconnect_attempts_total 27732
telemt_me_reconnect_success_total 17642
telemt_me_reader_eof_total 18960
telemt_me_idle_close_by_peer_total 18959
telemt_me_route_drop_no_conn_total 1439359
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3545745
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14140
telemt_desync_full_logged_total 3732
telemt_desync_suppressed_total 10408
telemt_desync_frames_bucket_total{bucket="1_2"} 3550
telemt_desync_frames_bucket_total{bucket="3_10"} 5354
telemt_desync_frames_bucket_total{bucket="gt_10"} 5236
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18198
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17629
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 556
telemt_user_connections_total{user="hello"} 3545551
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 48068005788 (44.77 GB)
telemt_user_octets_to_client{user="hello"} 1110890818124 (1.01 TB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22857.7 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333485
telemt_connections_bad_total 20174
telemt_handshake_timeouts_total 9199
telemt_upstream_connect_attempt_total 5323
telemt_upstream_connect_success_total 5236
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 5323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 6336
telemt_me_reconnect_success_total 4041
telemt_me_reader_eof_total 4287
telemt_me_idle_close_by_peer_total 4287
telemt_me_route_drop_no_conn_total 121076
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295748
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1109
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 532
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4166
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 4034
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 295777
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 2963421476 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 83531404560 (77.79 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 152814.3 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2861341
telemt_connections_bad_total 27822
telemt_handshake_timeouts_total 193262
telemt_upstream_connect_attempt_total 34181
telemt_upstream_connect_success_total 34170
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3286
telemt_me_reconnect_attempts_total 28795
telemt_me_reconnect_success_total 26243
telemt_me_reader_eof_total 27832
telemt_me_idle_close_by_peer_total 27831
telemt_me_route_drop_no_conn_total 968313
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2351905
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8290
telemt_desync_full_logged_total 2739
telemt_desync_suppressed_total 5551
telemt_desync_frames_bucket_total{bucket="1_2"} 1331
telemt_desync_frames_bucket_total{bucket="3_10"} 3018
telemt_desync_frames_bucket_total{bucket="gt_10"} 3941
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 26553
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26202
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 2351289
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 38465516412 (35.82 GB)
telemt_user_octets_to_client{user="hello"} 818523275825 (762.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 152814.7 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1825875
telemt_connections_bad_total 18156
telemt_handshake_timeouts_total 152637
telemt_upstream_connect_attempt_total 48017
telemt_upstream_connect_success_total 45683
telemt_upstream_connect_fail_total 2197
telemt_upstream_connect_attempts_per_request{bucket="1"} 47743
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2196
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11887
telemt_me_reconnect_attempts_total 41209
telemt_me_reconnect_success_total 32236
telemt_me_reader_eof_total 34622
telemt_me_idle_close_by_peer_total 34615
telemt_me_route_drop_no_conn_total 653801
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1514835
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3025
telemt_desync_full_logged_total 979
telemt_desync_suppressed_total 2046
telemt_desync_frames_bucket_total{bucket="1_2"} 814
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 963
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 32767
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32212
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 531
telemt_user_connections_total{user="hello"} 1519545
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 23513555117 (21.90 GB)
telemt_user_octets_to_client{user="hello"} 579570943498 (539.77 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22250.3 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360379
telemt_connections_bad_total 4135
telemt_handshake_timeouts_total 3292
telemt_upstream_connect_attempt_total 4832
telemt_upstream_connect_success_total 4689
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 4832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 14127
telemt_me_reconnect_success_total 3551
telemt_me_reader_eof_total 3952
telemt_me_idle_close_by_peer_total 3952
telemt_me_route_drop_no_conn_total 141695
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337210
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1164
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 800
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3903
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3547
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 352
telemt_user_connections_total{user="hello"} 337184
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 3909825320 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 108705546052 (101.24 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 117
```