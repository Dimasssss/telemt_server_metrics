# Server Metrics 2026-03-12 15:46:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 35258.8 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1269420
telemt_connections_bad_total 20235
telemt_handshake_timeouts_total 12549
telemt_upstream_connect_attempt_total 7077
telemt_upstream_connect_success_total 7038
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 7077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 418
telemt_me_reconnect_attempts_total 9132
telemt_me_reconnect_success_total 5225
telemt_me_reader_eof_total 5572
telemt_me_idle_close_by_peer_total 5571
telemt_me_route_drop_no_conn_total 454044
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1194322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6275
telemt_desync_full_logged_total 1567
telemt_desync_suppressed_total 4708
telemt_desync_frames_bucket_total{bucket="1_2"} 1614
telemt_desync_frames_bucket_total{bucket="3_10"} 2256
telemt_desync_frames_bucket_total{bucket="gt_10"} 2405
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5412
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5212
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 1194007
telemt_user_connections_current{user="hello"} 1777
telemt_user_octets_from_client{user="hello"} 18624880240 (17.35 GB)
telemt_user_octets_to_client{user="hello"} 346825146844 (323.01 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64879.5 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569878
telemt_connections_bad_total 7221
telemt_handshake_timeouts_total 27504
telemt_upstream_connect_attempt_total 15573
telemt_upstream_connect_success_total 15566
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 12194
telemt_me_reconnect_success_total 12126
telemt_me_reader_eof_total 12886
telemt_me_idle_close_by_peer_total 12886
telemt_me_route_drop_no_conn_total 167834
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509148
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1988
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1363
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 634
telemt_desync_frames_bucket_total{bucket="gt_10"} 472
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12245
telemt_me_writer_restored_same_endpoint_total 12117
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 509643
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 7901100711 (7.36 GB)
telemt_user_octets_to_client{user="hello"} 181579240870 (169.11 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 64879.3 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1208306
telemt_connections_bad_total 6252
telemt_handshake_timeouts_total 83890
telemt_upstream_connect_attempt_total 15599
telemt_upstream_connect_success_total 15594
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 991
telemt_me_reconnect_attempts_total 13208
telemt_me_reconnect_success_total 11984
telemt_me_reader_eof_total 12638
telemt_me_idle_close_by_peer_total 12638
telemt_me_route_drop_no_conn_total 326889
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892848
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3762
telemt_desync_full_logged_total 1153
telemt_desync_suppressed_total 2609
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 1365
telemt_desync_frames_bucket_total{bucket="gt_10"} 1829
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12070
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11943
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 893031
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 11836340732 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 279723788633 (260.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 64879.8 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717274
telemt_connections_bad_total 7708
telemt_handshake_timeouts_total 58103
telemt_upstream_connect_attempt_total 17066
telemt_upstream_connect_success_total 16997
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 17066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1382
telemt_me_reconnect_attempts_total 18987
telemt_me_reconnect_success_total 13745
telemt_me_reader_eof_total 14657
telemt_me_idle_close_by_peer_total 14657
telemt_me_route_drop_no_conn_total 244142
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617122
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1237
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 814
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14013
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13724
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 616609
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 7803241388 (7.27 GB)
telemt_user_octets_to_client{user="hello"} 243588412484 (226.86 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64879.6 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810877
telemt_connections_bad_total 8529
telemt_handshake_timeouts_total 6391
telemt_upstream_connect_attempt_total 20514
telemt_upstream_connect_success_total 20262
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 20514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 1122
telemt_me_reconnect_attempts_total 24250
telemt_me_reconnect_success_total 17012
telemt_me_reader_eof_total 17820
telemt_me_idle_close_by_peer_total 17820
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 283936
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747785
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2934
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 1940
telemt_desync_frames_bucket_total{bucket="1_2"} 833
telemt_desync_frames_bucket_total{bucket="3_10"} 1000
telemt_desync_frames_bucket_total{bucket="gt_10"} 1101
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 17415
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16978
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 403
telemt_user_connections_total{user="hello"} 747682
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 9043333928 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 209896888308 (195.48 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 119
```