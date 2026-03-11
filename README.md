# Server Metrics 2026-03-11 11:52:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 77141.2 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1751162
telemt_connections_bad_total 25384
telemt_handshake_timeouts_total 45187
telemt_upstream_connect_attempt_total 16075
telemt_upstream_connect_success_total 16066
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 828
telemt_me_reconnect_attempts_total 24995
telemt_me_reconnect_success_total 12173
telemt_me_reader_eof_total 13171
telemt_me_idle_close_by_peer_total 13171
telemt_me_route_drop_no_conn_total 644391
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1594738
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8368
telemt_desync_full_logged_total 2255
telemt_desync_suppressed_total 6113
telemt_desync_frames_bucket_total{bucket="1_2"} 2105
telemt_desync_frames_bucket_total{bucket="3_10"} 3200
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12701
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12167
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 528
telemt_user_connections_total{user="hello"} 1593289
telemt_user_connections_current{user="hello"} 1339
telemt_user_octets_from_client{user="hello"} 20613165812 (19.20 GB)
telemt_user_octets_to_client{user="hello"} 454267530032 (423.07 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77198.1 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662015
telemt_connections_bad_total 11856
telemt_handshake_timeouts_total 41990
telemt_upstream_connect_attempt_total 25296
telemt_upstream_connect_success_total 22357
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 25296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 2194
telemt_me_reconnect_attempts_total 16402
telemt_me_reconnect_success_total 15551
telemt_me_reader_eof_total 16449
telemt_me_idle_close_by_peer_total 16447
telemt_me_route_drop_no_conn_total 266620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560985
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2550
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1746
telemt_desync_frames_bucket_total{bucket="1_2"} 826
telemt_desync_frames_bucket_total{bucket="3_10"} 924
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15745
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15529
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 563210
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 5964248258 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 159650511700 (148.69 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 77198.0 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155275
telemt_connections_bad_total 7878
telemt_handshake_timeouts_total 108787
telemt_upstream_connect_attempt_total 20783
telemt_upstream_connect_success_total 20533
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 20783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 839
telemt_me_reconnect_attempts_total 29218
telemt_me_reconnect_success_total 15588
telemt_me_reader_eof_total 16736
telemt_me_idle_close_by_peer_total 16736
telemt_me_route_drop_no_conn_total 386529
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993270
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2698
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1896
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 1014
telemt_desync_frames_bucket_total{bucket="gt_10"} 1052
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 16218
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15577
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 994002
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 11549163641 (10.76 GB)
telemt_user_octets_to_client{user="hello"} 300841006989 (280.18 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 77198.4 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832878
telemt_connections_bad_total 72475
telemt_handshake_timeouts_total 76067
telemt_upstream_connect_attempt_total 20851
telemt_upstream_connect_success_total 20851
telemt_upstream_connect_attempts_per_request{bucket="1"} 20851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 845
telemt_me_reconnect_attempts_total 18067
telemt_me_reconnect_success_total 17006
telemt_me_reader_eof_total 18056
telemt_me_idle_close_by_peer_total 18055
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 265688
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660689
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1437
telemt_desync_full_logged_total 554
telemt_desync_suppressed_total 883
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17212
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16980
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 660055
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 7536977644 (7.02 GB)
telemt_user_octets_to_client{user="hello"} 187269989124 (174.41 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77198.1 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 898106
telemt_connections_bad_total 6241
telemt_handshake_timeouts_total 8581
telemt_upstream_connect_attempt_total 21182
telemt_upstream_connect_success_total 21089
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 893
telemt_me_reconnect_attempts_total 21184
telemt_me_reconnect_success_total 17125
telemt_me_reader_eof_total 18073
telemt_me_idle_close_by_peer_total 18073
telemt_me_route_drop_no_conn_total 315163
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815255
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3350
telemt_desync_full_logged_total 1240
telemt_desync_suppressed_total 2110
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 1313
telemt_desync_frames_bucket_total{bucket="gt_10"} 892
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17469
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17125
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 815012
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 12181732803 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 295564005462 (275.27 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 98
```