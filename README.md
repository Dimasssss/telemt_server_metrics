# Server Metrics 2026-03-10 23:30:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 32581.2 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761768
telemt_connections_bad_total 8947
telemt_handshake_timeouts_total 8508
telemt_upstream_connect_attempt_total 7064
telemt_upstream_connect_success_total 7055
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 368
telemt_me_reconnect_attempts_total 16997
telemt_me_reconnect_success_total 5335
telemt_me_reader_eof_total 5867
telemt_me_idle_close_by_peer_total 5867
telemt_me_route_drop_no_conn_total 315191
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721108
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3502
telemt_desync_full_logged_total 977
telemt_desync_suppressed_total 2525
telemt_desync_frames_bucket_total{bucket="1_2"} 1011
telemt_desync_frames_bucket_total{bucket="3_10"} 1311
telemt_desync_frames_bucket_total{bucket="gt_10"} 1180
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5743
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5329
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 720897
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 10115945844 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 216337800792 (201.48 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32637.9 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330421
telemt_connections_bad_total 2373
telemt_handshake_timeouts_total 17603
telemt_upstream_connect_attempt_total 13881
telemt_upstream_connect_success_total 11007
telemt_upstream_connect_fail_total 2874
telemt_upstream_connect_attempts_per_request{bucket="1"} 13881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2874
telemt_me_keepalive_timeout_total 1389
telemt_me_reconnect_attempts_total 7183
telemt_me_reconnect_success_total 6372
telemt_me_reader_eof_total 6710
telemt_me_idle_close_by_peer_total 6708
telemt_me_route_drop_no_conn_total 169780
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280175
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1706
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6464
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6351
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 282444
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2764720462 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 68958614760 (64.22 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 32637.6 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547140
telemt_connections_bad_total 3676
telemt_handshake_timeouts_total 33957
telemt_upstream_connect_attempt_total 8877
telemt_upstream_connect_success_total 8752
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 8877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 17050
telemt_me_reconnect_success_total 5993
telemt_me_reader_eof_total 6577
telemt_me_idle_close_by_peer_total 6577
telemt_me_route_drop_no_conn_total 189369
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481086
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6429
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5982
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 482016
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 6737415065 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 151353094781 (140.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 32638.0 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391933
telemt_connections_bad_total 31244
telemt_handshake_timeouts_total 35992
telemt_upstream_connect_attempt_total 9131
telemt_upstream_connect_success_total 9131
telemt_upstream_connect_attempts_per_request{bucket="1"} 9131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 8472
telemt_me_reconnect_success_total 7445
telemt_me_reader_eof_total 7848
telemt_me_idle_close_by_peer_total 7848
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 123568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311756
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7553
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7430
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 311431
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 4091970696 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 88680491784 (82.59 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32637.6 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414454
telemt_connections_bad_total 3195
telemt_handshake_timeouts_total 2677
telemt_upstream_connect_attempt_total 10001
telemt_upstream_connect_success_total 9962
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 10001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 12003
telemt_me_reconnect_success_total 8242
telemt_me_reader_eof_total 8655
telemt_me_idle_close_by_peer_total 8655
telemt_me_route_drop_no_conn_total 141488
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384349
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2218
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 815
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 8471
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8242
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 384139
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 6496594884 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 142029715724 (132.28 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 35
```