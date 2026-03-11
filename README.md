# Server Metrics 2026-03-11 00:56:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 37761.9 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798288
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9083
telemt_upstream_connect_attempt_total 8190
telemt_upstream_connect_success_total 8181
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 479
telemt_me_reconnect_attempts_total 17908
telemt_me_reconnect_success_total 6243
telemt_me_reader_eof_total 6841
telemt_me_idle_close_by_peer_total 6841
telemt_me_route_drop_no_conn_total 327943
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 755900
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3566
telemt_desync_full_logged_total 997
telemt_desync_suppressed_total 2569
telemt_desync_frames_bucket_total{bucket="1_2"} 1040
telemt_desync_frames_bucket_total{bucket="3_10"} 1322
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6660
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6237
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 755674
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 10503350116 (9.78 GB)
telemt_user_octets_to_client{user="hello"} 227969134508 (212.31 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37818.6 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344216
telemt_connections_bad_total 2392
telemt_handshake_timeouts_total 17674
telemt_upstream_connect_attempt_total 15313
telemt_upstream_connect_success_total 12433
telemt_upstream_connect_fail_total 2880
telemt_upstream_connect_attempts_per_request{bucket="1"} 15313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2880
telemt_me_keepalive_timeout_total 1707
telemt_me_reconnect_attempts_total 8392
telemt_me_reconnect_success_total 7578
telemt_me_reader_eof_total 7992
telemt_me_idle_close_by_peer_total 7990
telemt_me_route_drop_no_conn_total 173070
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293554
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1770
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1266
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 628
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7681
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7557
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 295823
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2844129110 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 70433438440 (65.60 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 37818.4 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 572317
telemt_connections_bad_total 4060
telemt_handshake_timeouts_total 34162
telemt_upstream_connect_attempt_total 10331
telemt_upstream_connect_success_total 10188
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 10331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 510
telemt_me_reconnect_attempts_total 18269
telemt_me_reconnect_success_total 7207
telemt_me_reader_eof_total 7859
telemt_me_idle_close_by_peer_total 7859
telemt_me_route_drop_no_conn_total 196144
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505542
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7652
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7196
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 506461
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 6849317281 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 155183829913 (144.53 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 37818.9 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419830
telemt_connections_bad_total 35962
telemt_handshake_timeouts_total 39541
telemt_upstream_connect_attempt_total 10777
telemt_upstream_connect_success_total 10777
telemt_upstream_connect_attempts_per_request{bucket="1"} 10777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 408
telemt_me_reconnect_attempts_total 9902
telemt_me_reconnect_success_total 8869
telemt_me_reader_eof_total 9372
telemt_me_idle_close_by_peer_total 9372
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 128953
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331290
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 8986
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8853
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 330966
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 4211372624 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 91069051132 (84.81 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37818.5 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443803
telemt_connections_bad_total 4404
telemt_handshake_timeouts_total 2790
telemt_upstream_connect_attempt_total 11360
telemt_upstream_connect_success_total 11313
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 11360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 13139
telemt_me_reconnect_success_total 9372
telemt_me_reader_eof_total 9856
telemt_me_idle_close_by_peer_total 9856
telemt_me_route_drop_no_conn_total 147788
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408492
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2274
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 838
telemt_desync_frames_bucket_total{bucket="3_10"} 971
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 9611
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9372
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 408213
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 8366270972 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 146904434708 (136.82 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```