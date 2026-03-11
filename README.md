# Server Metrics 2026-03-11 02:48:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 44466.5 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863173
telemt_connections_bad_total 10062
telemt_handshake_timeouts_total 16267
telemt_upstream_connect_attempt_total 9690
telemt_upstream_connect_success_total 9681
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 510
telemt_me_reconnect_attempts_total 19061
telemt_me_reconnect_success_total 7391
telemt_me_reader_eof_total 8074
telemt_me_idle_close_by_peer_total 8074
telemt_me_route_drop_no_conn_total 344289
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808247
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3712
telemt_desync_full_logged_total 1040
telemt_desync_suppressed_total 2672
telemt_desync_frames_bucket_total{bucket="1_2"} 1080
telemt_desync_frames_bucket_total{bucket="3_10"} 1397
telemt_desync_frames_bucket_total{bucket="gt_10"} 1235
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7819
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7385
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 807981
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 10933013868 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 240908926832 (224.36 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44523.2 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363099
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 18226
telemt_upstream_connect_attempt_total 17419
telemt_upstream_connect_success_total 14529
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 17419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1747
telemt_me_reconnect_attempts_total 10141
telemt_me_reconnect_success_total 9324
telemt_me_reader_eof_total 9834
telemt_me_idle_close_by_peer_total 9832
telemt_me_route_drop_no_conn_total 177903
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311175
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 9439
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9303
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 313445
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 2957442770 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 73260951428 (68.23 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 44523.0 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606504
telemt_connections_bad_total 4921
telemt_handshake_timeouts_total 34668
telemt_upstream_connect_attempt_total 12155
telemt_upstream_connect_success_total 11992
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 19727
telemt_me_reconnect_success_total 8659
telemt_me_reader_eof_total 9406
telemt_me_idle_close_by_peer_total 9406
telemt_me_route_drop_no_conn_total 206222
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 1099
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 540
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9122
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8648
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 538998
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 7030880169 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 165679884133 (154.30 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 44523.4 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455688
telemt_connections_bad_total 42098
telemt_handshake_timeouts_total 44253
telemt_upstream_connect_attempt_total 12974
telemt_upstream_connect_success_total 12974
telemt_upstream_connect_attempts_per_request{bucket="1"} 12974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 459
telemt_me_reconnect_attempts_total 11756
telemt_me_reconnect_success_total 10718
telemt_me_reader_eof_total 11372
telemt_me_idle_close_by_peer_total 11372
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 136355
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355692
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 10847
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10699
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 355361
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 4353652180 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 94910821300 (88.39 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44523.1 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480400
telemt_connections_bad_total 5792
telemt_handshake_timeouts_total 3030
telemt_upstream_connect_attempt_total 13124
telemt_upstream_connect_success_total 13069
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 13124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 529
telemt_me_reconnect_attempts_total 14550
telemt_me_reconnect_success_total 10775
telemt_me_reader_eof_total 11362
telemt_me_idle_close_by_peer_total 11362
telemt_me_route_drop_no_conn_total 155324
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438008
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2315
telemt_desync_full_logged_total 903
telemt_desync_suppressed_total 1412
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 11031
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10775
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 437674
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 8536071148 (7.95 GB)
telemt_user_octets_to_client{user="hello"} 158165777060 (147.30 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 51
```