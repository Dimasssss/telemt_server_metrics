# Server Metrics 2026-03-11 02:02:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 41723.6 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829735
telemt_connections_bad_total 9537
telemt_handshake_timeouts_total 11676
telemt_upstream_connect_attempt_total 9088
telemt_upstream_connect_success_total 9079
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 18588
telemt_me_reconnect_success_total 6921
telemt_me_reader_eof_total 7569
telemt_me_idle_close_by_peer_total 7569
telemt_me_route_drop_no_conn_total 336840
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784300
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3640
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 2616
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7342
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6915
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 784037
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 10686756972 (9.95 GB)
telemt_user_octets_to_client{user="hello"} 236829601300 (220.56 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41780.2 (11h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355519
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 18035
telemt_upstream_connect_attempt_total 16529
telemt_upstream_connect_success_total 13640
telemt_upstream_connect_fail_total 2889
telemt_upstream_connect_attempts_per_request{bucket="1"} 16529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2889
telemt_me_keepalive_timeout_total 1728
telemt_me_reconnect_attempts_total 9383
telemt_me_reconnect_success_total 8566
telemt_me_reader_eof_total 9039
telemt_me_idle_close_by_peer_total 9037
telemt_me_route_drop_no_conn_total 175726
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304235
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8678
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8545
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 306505
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2883213522 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 72191997832 (67.23 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 41780.2 (11h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592131
telemt_connections_bad_total 4889
telemt_handshake_timeouts_total 34367
telemt_upstream_connect_attempt_total 11473
telemt_upstream_connect_success_total 11317
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 11473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 529
telemt_me_reconnect_attempts_total 19181
telemt_me_reconnect_success_total 8116
telemt_me_reader_eof_total 8825
telemt_me_idle_close_by_peer_total 8825
telemt_me_route_drop_no_conn_total 201623
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1527
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8571
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8105
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 525076
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 6963320321 (6.49 GB)
telemt_user_octets_to_client{user="hello"} 159878657853 (148.90 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 41780.4 (11h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440594
telemt_connections_bad_total 39603
telemt_handshake_timeouts_total 42366
telemt_upstream_connect_attempt_total 12125
telemt_upstream_connect_success_total 12125
telemt_upstream_connect_attempts_per_request{bucket="1"} 12125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 11036
telemt_me_reconnect_success_total 10001
telemt_me_reader_eof_total 10596
telemt_me_idle_close_by_peer_total 10596
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 132743
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345098
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 737
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 443
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10124
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9982
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 344768
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 4275176668 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 92922818432 (86.54 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41780.2 (11h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465564
telemt_connections_bad_total 5790
telemt_handshake_timeouts_total 2983
telemt_upstream_connect_attempt_total 12409
telemt_upstream_connect_success_total 12357
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 522
telemt_me_reconnect_attempts_total 13967
telemt_me_reconnect_success_total 10195
telemt_me_reader_eof_total 10745
telemt_me_idle_close_by_peer_total 10745
telemt_me_route_drop_no_conn_total 151848
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425389
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2301
telemt_desync_full_logged_total 894
telemt_desync_suppressed_total 1407
telemt_desync_frames_bucket_total{bucket="1_2"} 853
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 10446
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10195
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 425069
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 8447128828 (7.87 GB)
telemt_user_octets_to_client{user="hello"} 150650580948 (140.30 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 36
```