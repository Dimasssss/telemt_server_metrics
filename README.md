# Server Metrics 2026-03-11 13:04:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 81430.0 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1904120
telemt_connections_bad_total 27770
telemt_handshake_timeouts_total 49037
telemt_upstream_connect_attempt_total 16889
telemt_upstream_connect_success_total 16880
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 876
telemt_me_reconnect_attempts_total 25590
telemt_me_reconnect_success_total 12760
telemt_me_reader_eof_total 13796
telemt_me_idle_close_by_peer_total 13796
telemt_me_route_drop_no_conn_total 701283
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1737890
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9082
telemt_desync_full_logged_total 2456
telemt_desync_suppressed_total 6626
telemt_desync_frames_bucket_total{bucket="1_2"} 2261
telemt_desync_frames_bucket_total{bucket="3_10"} 3486
telemt_desync_frames_bucket_total{bucket="gt_10"} 3335
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13297
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12754
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1736415
telemt_user_connections_current{user="hello"} 1645
telemt_user_octets_from_client{user="hello"} 22903239716 (21.33 GB)
telemt_user_octets_to_client{user="hello"} 491913474968 (458.13 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81486.7 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 724374
telemt_connections_bad_total 13029
telemt_handshake_timeouts_total 50486
telemt_upstream_connect_attempt_total 26322
telemt_upstream_connect_success_total 23378
telemt_upstream_connect_fail_total 2944
telemt_upstream_connect_attempts_per_request{bucket="1"} 26322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2944
telemt_me_keepalive_timeout_total 2439
telemt_me_reconnect_attempts_total 17206
telemt_me_reconnect_success_total 16343
telemt_me_reader_eof_total 17299
telemt_me_idle_close_by_peer_total 17296
telemt_me_route_drop_no_conn_total 283870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608908
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2685
telemt_desync_full_logged_total 849
telemt_desync_suppressed_total 1836
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 861
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 16552
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16320
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 611273
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 6554344150 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 175077352108 (163.05 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 81486.6 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244242
telemt_connections_bad_total 8114
telemt_handshake_timeouts_total 115626
telemt_upstream_connect_attempt_total 21804
telemt_upstream_connect_success_total 21537
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 21804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 876
telemt_me_reconnect_attempts_total 32458
telemt_me_reconnect_success_total 16357
telemt_me_reader_eof_total 17601
telemt_me_idle_close_by_peer_total 17601
telemt_me_route_drop_no_conn_total 430472
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1073923
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2897
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 2033
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1089
telemt_desync_frames_bucket_total{bucket="gt_10"} 1108
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 17075
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16346
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 1074306
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 12696754697 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 322306103697 (300.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 81487.1 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 898920
telemt_connections_bad_total 76523
telemt_handshake_timeouts_total 84125
telemt_upstream_connect_attempt_total 22234
telemt_upstream_connect_success_total 22234
telemt_upstream_connect_attempts_per_request{bucket="1"} 22234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 896
telemt_me_reconnect_attempts_total 19227
telemt_me_reconnect_success_total 18159
telemt_me_reader_eof_total 19251
telemt_me_idle_close_by_peer_total 19250
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 288365
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713141
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1513
telemt_desync_full_logged_total 591
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18383
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18132
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 712499
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 8244309008 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 204935060784 (190.86 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81486.8 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975729
telemt_connections_bad_total 6807
telemt_handshake_timeouts_total 9013
telemt_upstream_connect_attempt_total 22218
telemt_upstream_connect_success_total 22122
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 22218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 21991
telemt_me_reconnect_success_total 17921
telemt_me_reader_eof_total 18906
telemt_me_idle_close_by_peer_total 18906
telemt_me_route_drop_no_conn_total 343767
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886016
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3575
telemt_desync_full_logged_total 1321
telemt_desync_suppressed_total 2254
telemt_desync_frames_bucket_total{bucket="1_2"} 1245
telemt_desync_frames_bucket_total{bucket="3_10"} 1366
telemt_desync_frames_bucket_total{bucket="gt_10"} 964
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18277
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17921
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 885766
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 13002657715 (12.11 GB)
telemt_user_octets_to_client{user="hello"} 317513748242 (295.71 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 126
```