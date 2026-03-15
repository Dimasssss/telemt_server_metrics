# Server Metrics 2026-03-15 11:36:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 48135.2 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1279463
telemt_connections_bad_total 78492
telemt_handshake_timeouts_total 10630
telemt_upstream_connect_attempt_total 9692
telemt_upstream_connect_success_total 9650
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 9738
telemt_me_reconnect_success_total 7231
telemt_me_reader_eof_total 7701
telemt_me_idle_close_by_peer_total 7701
telemt_me_route_drop_no_conn_total 425990
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075795
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4112
telemt_desync_full_logged_total 1165
telemt_desync_suppressed_total 2947
telemt_desync_frames_bucket_total{bucket="1_2"} 995
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1499
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7416
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7220
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 1075583
telemt_user_connections_current{user="hello"} 2252
telemt_user_octets_from_client{user="hello"} 15055849044 (14.02 GB)
telemt_user_octets_to_client{user="hello"} 434389355416 (404.56 GB)
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 48135.0 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499948
telemt_connections_bad_total 26769
telemt_handshake_timeouts_total 22075
telemt_upstream_connect_attempt_total 12602
telemt_upstream_connect_success_total 12537
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9857
telemt_me_reconnect_success_total 9792
telemt_me_reader_eof_total 10356
telemt_me_idle_close_by_peer_total 10356
telemt_me_route_drop_no_conn_total 128589
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394936
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1474
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 970
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9897
telemt_me_writer_restored_same_endpoint_total 9780
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 395206
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 5658404031 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 148513309068 (138.31 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 48134.9 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979901
telemt_connections_bad_total 31708
telemt_handshake_timeouts_total 98518
telemt_upstream_connect_attempt_total 10649
telemt_upstream_connect_success_total 10600
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 8224
telemt_me_reconnect_success_total 8170
telemt_me_reader_eof_total 8639
telemt_me_idle_close_by_peer_total 8639
telemt_me_route_drop_no_conn_total 277830
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688125
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1702
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1100
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 689
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8278
telemt_me_writer_restored_same_endpoint_total 8151
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 686741
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 10238175612 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 266215931048 (247.93 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 48134.8 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510357
telemt_connections_bad_total 62895
telemt_handshake_timeouts_total 27179
telemt_upstream_connect_attempt_total 14224
telemt_upstream_connect_success_total 13859
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 14224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 35418
telemt_me_reconnect_success_total 11436
telemt_me_reader_eof_total 12521
telemt_me_idle_close_by_peer_total 12521
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 143665
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382211
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 977
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 398
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12295
telemt_me_refill_failed_total 749
telemt_me_writer_restored_same_endpoint_total 11404
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 859
telemt_user_connections_total{user="hello"} 382110
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 4672299580 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 120955374128 (112.65 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 48135.6 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535204
telemt_connections_bad_total 6570
telemt_handshake_timeouts_total 11619
telemt_upstream_connect_attempt_total 10743
telemt_upstream_connect_success_total 10690
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 10743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 8322
telemt_me_reconnect_success_total 8276
telemt_me_reader_eof_total 8792
telemt_me_idle_close_by_peer_total 8792
telemt_me_route_drop_no_conn_total 137869
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441327
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1736
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1169
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 706
telemt_desync_frames_bucket_total{bucket="gt_10"} 538
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8369
telemt_me_writer_restored_same_endpoint_total 8268
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 441351
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 5872034304 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 161465493504 (150.38 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 122
```