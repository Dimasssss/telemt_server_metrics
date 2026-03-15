# Server Metrics 2026-03-15 10:55:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 45684.7 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143293
telemt_connections_bad_total 68619
telemt_handshake_timeouts_total 9511
telemt_upstream_connect_attempt_total 9161
telemt_upstream_connect_success_total 9122
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9345
telemt_me_reconnect_success_total 6841
telemt_me_reader_eof_total 7297
telemt_me_idle_close_by_peer_total 7297
telemt_me_route_drop_no_conn_total 382342
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 966492
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3649
telemt_desync_full_logged_total 1026
telemt_desync_suppressed_total 2623
telemt_desync_frames_bucket_total{bucket="1_2"} 904
telemt_desync_frames_bucket_total{bucket="3_10"} 1417
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7018
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 6830
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 966498
telemt_user_connections_current{user="hello"} 2013
telemt_user_octets_from_client{user="hello"} 13695581312 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 388916140200 (362.21 GB)
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 45685.4 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450403
telemt_connections_bad_total 24459
telemt_handshake_timeouts_total 19344
telemt_upstream_connect_attempt_total 12107
telemt_upstream_connect_success_total 12043
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9497
telemt_me_reconnect_success_total 9437
telemt_me_reader_eof_total 9987
telemt_me_idle_close_by_peer_total 9987
telemt_me_route_drop_no_conn_total 114721
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356012
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1247
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 809
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9533
telemt_me_writer_restored_same_endpoint_total 9429
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 356298
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 5200714227 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 134870743716 (125.61 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 45685.3 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 867946
telemt_connections_bad_total 28991
telemt_handshake_timeouts_total 84272
telemt_upstream_connect_attempt_total 10069
telemt_upstream_connect_success_total 10026
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 7785
telemt_me_reconnect_success_total 7734
telemt_me_reader_eof_total 8189
telemt_me_idle_close_by_peer_total 8189
telemt_me_route_drop_no_conn_total 235335
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623967
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1468
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 943
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 7836
telemt_me_writer_restored_same_endpoint_total 7715
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 623384
telemt_user_connections_current{user="hello"} 1217
telemt_user_octets_from_client{user="hello"} 9202735628 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 246422187560 (229.50 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 45685.2 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465031
telemt_connections_bad_total 57531
telemt_handshake_timeouts_total 26169
telemt_upstream_connect_attempt_total 13701
telemt_upstream_connect_success_total 13358
telemt_upstream_connect_fail_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 13701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 343
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31436
telemt_me_reconnect_success_total 11072
telemt_me_reader_eof_total 12036
telemt_me_idle_close_by_peer_total 12036
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 130092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349472
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 832
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 623
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11809
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 11040
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 349378
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 4127955744 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 109654629648 (102.12 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 45686.0 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478204
telemt_connections_bad_total 6154
telemt_handshake_timeouts_total 8643
telemt_upstream_connect_attempt_total 10097
telemt_upstream_connect_success_total 10049
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 7813
telemt_me_reconnect_success_total 7773
telemt_me_reader_eof_total 8259
telemt_me_idle_close_by_peer_total 8259
telemt_me_route_drop_no_conn_total 124297
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395110
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1546
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1049
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 631
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7861
telemt_me_writer_restored_same_endpoint_total 7765
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 395127
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 4919060428 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 148332088272 (138.15 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 126
```