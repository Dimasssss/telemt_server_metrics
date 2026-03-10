# Server Metrics 2026-03-10 21:38:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25867.3 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702528
telemt_connections_bad_total 8154
telemt_handshake_timeouts_total 8155
telemt_upstream_connect_attempt_total 5602
telemt_upstream_connect_success_total 5593
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 351
telemt_me_reconnect_attempts_total 15882
telemt_me_reconnect_success_total 4224
telemt_me_reader_eof_total 4673
telemt_me_idle_close_by_peer_total 4673
telemt_me_route_drop_no_conn_total 293202
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663995
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3330
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2397
telemt_desync_frames_bucket_total{bucket="1_2"} 945
telemt_desync_frames_bucket_total{bucket="3_10"} 1257
telemt_desync_frames_bucket_total{bucket="gt_10"} 1128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4620
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4218
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 663800
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 9590009556 (8.93 GB)
telemt_user_octets_to_client{user="hello"} 201118641100 (187.31 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25923.9 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307668
telemt_connections_bad_total 2106
telemt_handshake_timeouts_total 17369
telemt_upstream_connect_attempt_total 11975
telemt_upstream_connect_success_total 9113
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 11975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 5636
telemt_me_reconnect_success_total 4831
telemt_me_reader_eof_total 5065
telemt_me_idle_close_by_peer_total 5063
telemt_me_route_drop_no_conn_total 163036
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258433
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1512
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 1094
telemt_desync_frames_bucket_total{bucket="1_2"} 467
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 509
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4915
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4810
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 260706
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 2612169530 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 61503320504 (57.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 25923.8 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502949
telemt_connections_bad_total 2901
telemt_handshake_timeouts_total 33567
telemt_upstream_connect_attempt_total 7309
telemt_upstream_connect_success_total 7195
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 7309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 15838
telemt_me_reconnect_success_total 4791
telemt_me_reader_eof_total 5280
telemt_me_idle_close_by_peer_total 5280
telemt_me_route_drop_no_conn_total 174572
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438379
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1421
telemt_desync_full_logged_total 395
telemt_desync_suppressed_total 1026
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 486
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5212
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4780
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 439312
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 6380199785 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 142215620097 (132.45 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 25924.3 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347275
telemt_connections_bad_total 25147
telemt_handshake_timeouts_total 30482
telemt_upstream_connect_attempt_total 6981
telemt_upstream_connect_success_total 6981
telemt_upstream_connect_attempts_per_request{bucket="1"} 6981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 6672
telemt_me_reconnect_success_total 5650
telemt_me_reader_eof_total 5928
telemt_me_idle_close_by_peer_total 5928
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 113440
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279049
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5746
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5637
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 278727
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 3973016144 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 84582313076 (78.77 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25924.0 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366665
telemt_connections_bad_total 1126
telemt_handshake_timeouts_total 2329
telemt_upstream_connect_attempt_total 7963
telemt_upstream_connect_success_total 7933
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 10327
telemt_me_reconnect_success_total 6573
telemt_me_reader_eof_total 6890
telemt_me_idle_close_by_peer_total 6890
telemt_me_route_drop_no_conn_total 130415
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343724
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2060
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1294
telemt_desync_frames_bucket_total{bucket="1_2"} 766
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6786
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6573
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 343588
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 6333655168 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 120901166076 (112.60 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 52
```