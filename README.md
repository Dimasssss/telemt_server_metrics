# Server Metrics 2026-03-05 00:53:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 14384.3 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121753
telemt_connections_bad_total 9113
telemt_handshake_timeouts_total 825
telemt_upstream_connect_attempt_total 22122
telemt_upstream_connect_success_total 21939
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 21938
telemt_upstream_connect_attempts_per_request{bucket="2"} 60
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 607
telemt_me_reconnect_attempts_total 11175
telemt_me_reconnect_success_total 11159
telemt_me_reader_eof_total 11613
telemt_me_idle_close_by_peer_total 11612
telemt_me_route_drop_no_conn_total 31297
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 11672
telemt_me_writer_restored_same_endpoint_total 11139
telemt_me_writer_removed_unexpected_minus_restored_total 533
telemt_user_connections_total{user="hello"} 99990
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 2940060344 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 54409878832 (50.67 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 14379.1 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43787
telemt_connections_bad_total 801
telemt_handshake_timeouts_total 1059
telemt_upstream_connect_attempt_total 16716
telemt_upstream_connect_success_total 16391
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 16381
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1038
telemt_me_reconnect_attempts_total 6582
telemt_me_reconnect_success_total 6554
telemt_me_reader_eof_total 6664
telemt_me_idle_close_by_peer_total 6663
telemt_me_route_drop_no_conn_total 13440
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 139
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 6768
telemt_me_writer_restored_same_endpoint_total 6529
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 39558
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 345030420 (329.05 MB)
telemt_user_octets_to_client{user="hello"} 10739966164 (10.00 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 14375.8 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100991
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 7418
telemt_upstream_connect_success_total 7360
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 7360
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 677
telemt_me_reconnect_success_total 685
telemt_me_reader_eof_total 681
telemt_me_idle_close_by_peer_total 681
telemt_me_route_drop_no_conn_total 28963
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 175
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_restored_same_endpoint_total 665
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 92987
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1093160544 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 36610358024 (34.10 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 46424.1 (12h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559411
telemt_connections_bad_total 83312
telemt_handshake_timeouts_total 14741
telemt_upstream_connect_attempt_total 21837
telemt_upstream_connect_success_total 21835
telemt_upstream_connect_attempts_per_request{bucket="1"} 21835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 3176
telemt_me_reconnect_success_total 3155
telemt_me_reader_eof_total 3215
telemt_me_idle_close_by_peer_total 3215
telemt_me_route_drop_no_conn_total 187611
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 726
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 18
telemt_pool_force_close_total 507
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 3216
telemt_me_writer_restored_same_endpoint_total 3128
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 432809
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 5870543932 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 161011309124 (149.95 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 46783.1 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541816
telemt_connections_bad_total 3866
telemt_handshake_timeouts_total 5925
telemt_upstream_connect_attempt_total 30253
telemt_upstream_connect_success_total 30092
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 30092
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 456
telemt_me_reconnect_attempts_total 6652
telemt_me_reconnect_success_total 6630
telemt_me_reader_eof_total 6879
telemt_me_idle_close_by_peer_total 6878
telemt_me_route_drop_no_conn_total 238200
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 843
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6884
telemt_me_writer_restored_same_endpoint_total 6608
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 491180
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 7397918344 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 164084050936 (152.82 GB)
telemt_user_unique_ips_current{user="hello"} 24
```