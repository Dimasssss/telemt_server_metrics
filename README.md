# Server Metrics 2026-03-11 05:56:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 55745.4 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090092
telemt_connections_bad_total 13230
telemt_handshake_timeouts_total 37991
telemt_upstream_connect_attempt_total 11819
telemt_upstream_connect_success_total 11810
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 551
telemt_me_reconnect_attempts_total 20672
telemt_me_reconnect_success_total 8992
telemt_me_reader_eof_total 9783
telemt_me_idle_close_by_peer_total 9783
telemt_me_route_drop_no_conn_total 400601
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 978185
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4523
telemt_desync_full_logged_total 1279
telemt_desync_suppressed_total 3244
telemt_desync_frames_bucket_total{bucket="1_2"} 1242
telemt_desync_frames_bucket_total{bucket="3_10"} 1709
telemt_desync_frames_bucket_total{bucket="gt_10"} 1572
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9439
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8986
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 977887
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 13178757964 (12.27 GB)
telemt_user_octets_to_client{user="hello"} 285237814312 (265.65 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55802.3 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420362
telemt_connections_bad_total 3804
telemt_handshake_timeouts_total 19986
telemt_upstream_connect_attempt_total 20437
telemt_upstream_connect_success_total 17530
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 1793
telemt_me_reconnect_attempts_total 12621
telemt_me_reconnect_success_total 11798
telemt_me_reader_eof_total 12465
telemt_me_idle_close_by_peer_total 12463
telemt_me_route_drop_no_conn_total 194808
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360673
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1885
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1321
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 676
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11934
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11777
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 362944
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 3662431966 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 89060831248 (82.94 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 55802.1 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718006
telemt_connections_bad_total 6072
telemt_handshake_timeouts_total 39346
telemt_upstream_connect_attempt_total 15091
telemt_upstream_connect_success_total 14891
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 15091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 579
telemt_me_reconnect_attempts_total 22107
telemt_me_reconnect_success_total 11034
telemt_me_reader_eof_total 11897
telemt_me_idle_close_by_peer_total 11897
telemt_me_route_drop_no_conn_total 241848
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641509
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1833
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1303
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11523
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11023
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 642363
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 7723820473 (7.19 GB)
telemt_user_octets_to_client{user="hello"} 190230787805 (177.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 55802.5 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546262
telemt_connections_bad_total 52390
telemt_handshake_timeouts_total 56997
telemt_upstream_connect_attempt_total 15995
telemt_upstream_connect_success_total 15995
telemt_upstream_connect_attempts_per_request{bucket="1"} 15995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 14257
telemt_me_reconnect_success_total 13213
telemt_me_reader_eof_total 14022
telemt_me_idle_close_by_peer_total 14022
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 161366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422098
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 898
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 13364
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13191
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 421675
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 5109918036 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 115818622032 (107.86 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55802.2 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570082
telemt_connections_bad_total 5958
telemt_handshake_timeouts_total 3873
telemt_upstream_connect_attempt_total 15920
telemt_upstream_connect_success_total 15853
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 15920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 566
telemt_me_reconnect_attempts_total 16812
telemt_me_reconnect_success_total 13029
telemt_me_reader_eof_total 13754
telemt_me_idle_close_by_peer_total 13754
telemt_me_route_drop_no_conn_total 186179
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521109
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2529
telemt_desync_full_logged_total 978
telemt_desync_suppressed_total 1551
telemt_desync_frames_bucket_total{bucket="1_2"} 914
telemt_desync_frames_bucket_total{bucket="3_10"} 1075
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13313
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13029
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 520765
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 9258956456 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 181500003952 (169.04 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 74
```