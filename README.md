# Server Metrics 2026-03-10 23:55:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 34104.8 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771702
telemt_connections_bad_total 8949
telemt_handshake_timeouts_total 8578
telemt_upstream_connect_attempt_total 7382
telemt_upstream_connect_success_total 7373
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 462
telemt_me_reconnect_attempts_total 17272
telemt_me_reconnect_success_total 5610
telemt_me_reader_eof_total 6159
telemt_me_idle_close_by_peer_total 6159
telemt_me_route_drop_no_conn_total 319178
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730775
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3525
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 2540
telemt_desync_frames_bucket_total{bucket="1_2"} 1021
telemt_desync_frames_bucket_total{bucket="3_10"} 1314
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 6020
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5604
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 730564
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 10152897404 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 217575351124 (202.63 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34161.5 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333867
telemt_connections_bad_total 2382
telemt_handshake_timeouts_total 17616
telemt_upstream_connect_attempt_total 14265
telemt_upstream_connect_success_total 11389
telemt_upstream_connect_fail_total 2876
telemt_upstream_connect_attempts_per_request{bucket="1"} 14265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2876
telemt_me_keepalive_timeout_total 1699
telemt_me_reconnect_attempts_total 7522
telemt_me_reconnect_success_total 6710
telemt_me_reader_eof_total 7065
telemt_me_idle_close_by_peer_total 7063
telemt_me_route_drop_no_conn_total 170701
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283490
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1722
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1241
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6805
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6689
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 285759
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 2777602786 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 69195630952 (64.44 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 34161.3 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554667
telemt_connections_bad_total 3855
telemt_handshake_timeouts_total 33996
telemt_upstream_connect_attempt_total 9219
telemt_upstream_connect_success_total 9092
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 9219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 495
telemt_me_reconnect_attempts_total 17346
telemt_me_reconnect_success_total 6288
telemt_me_reader_eof_total 6887
telemt_me_idle_close_by_peer_total 6887
telemt_me_route_drop_no_conn_total 191490
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488344
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6728
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6277
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 489269
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 6764079557 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 152415954741 (141.95 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 34161.7 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400189
telemt_connections_bad_total 32629
telemt_handshake_timeouts_total 36959
telemt_upstream_connect_attempt_total 9553
telemt_upstream_connect_success_total 9553
telemt_upstream_connect_attempts_per_request{bucket="1"} 9553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 392
telemt_me_reconnect_attempts_total 8851
telemt_me_reconnect_success_total 7822
telemt_me_reader_eof_total 8241
telemt_me_idle_close_by_peer_total 8241
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 125232
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317633
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7935
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7807
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 317308
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 4111263820 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 89464828612 (83.32 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34161.3 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423514
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 2695
telemt_upstream_connect_attempt_total 10356
telemt_upstream_connect_success_total 10316
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 496
telemt_me_reconnect_attempts_total 12314
telemt_me_reconnect_success_total 8551
telemt_me_reader_eof_total 8980
telemt_me_idle_close_by_peer_total 8980
telemt_me_route_drop_no_conn_total 143729
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392281
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2246
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1382
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 963
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8782
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8551
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 392051
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 6543887592 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 143856796732 (133.98 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```