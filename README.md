# Server Metrics 2026-03-04 05:02:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 28331.7 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201417
telemt_connections_bad_total 1636
telemt_handshake_timeouts_total 3794
telemt_upstream_connect_attempt_total 20015
telemt_upstream_connect_success_total 19925
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 19925
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 4522
telemt_me_reconnect_success_total 4504
telemt_me_reader_eof_total 4609
telemt_me_idle_close_by_peer_total 4609
telemt_me_route_drop_no_conn_total 65341
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 539
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4609
telemt_me_writer_restored_same_endpoint_total 4484
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 191038
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 2028504260 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 61337019000 (57.12 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 28328.1 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96063
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 20934
telemt_upstream_connect_attempt_total 64521
telemt_upstream_connect_success_total 63825
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 63819
telemt_upstream_connect_attempts_per_request{bucket="2"} 337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_keepalive_timeout_total 983
telemt_me_reconnect_attempts_total 39362
telemt_me_reconnect_success_total 39334
telemt_me_reader_eof_total 40325
telemt_me_idle_close_by_peer_total 40324
telemt_me_route_drop_no_conn_total 29763
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 40386
telemt_me_writer_restored_same_endpoint_total 39313
telemt_me_writer_removed_unexpected_minus_restored_total 1073
telemt_user_connections_total{user="hello"} 69244
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 628653148 (599.53 MB)
telemt_user_octets_to_client{user="hello"} 30115611228 (28.05 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 28327.0 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212737
telemt_connections_bad_total 78208
telemt_handshake_timeouts_total 4431
telemt_upstream_connect_attempt_total 36948
telemt_upstream_connect_success_total 36703
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 36703
telemt_upstream_connect_attempts_per_request{bucket="2"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 486
telemt_me_reconnect_attempts_total 14822
telemt_me_reconnect_success_total 14783
telemt_me_reader_eof_total 15566
telemt_me_idle_close_by_peer_total 15563
telemt_me_route_drop_no_conn_total 43162
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 317
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 15574
telemt_me_writer_restored_same_endpoint_total 14762
telemt_me_writer_removed_unexpected_minus_restored_total 812
telemt_user_connections_total{user="hello"} 125844
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 808390744 (770.94 MB)
telemt_user_octets_to_client{user="hello"} 32353689360 (30.13 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 28326.0 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106602
telemt_connections_bad_total 6233
telemt_handshake_timeouts_total 1227
telemt_upstream_connect_attempt_total 19551
telemt_upstream_connect_success_total 19468
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 19468
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 3136
telemt_me_reconnect_success_total 3135
telemt_me_reader_eof_total 3162
telemt_me_idle_close_by_peer_total 3162
telemt_me_route_drop_no_conn_total 34041
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 3162
telemt_me_writer_restored_same_endpoint_total 3114
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 94677
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 786790472 (750.34 MB)
telemt_user_octets_to_client{user="hello"} 32170757148 (29.96 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 28324.5 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230929
telemt_connections_bad_total 5037
telemt_handshake_timeouts_total 103984
telemt_upstream_connect_attempt_total 41635
telemt_upstream_connect_success_total 41350
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 41350
telemt_upstream_connect_attempts_per_request{bucket="2"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 20100
telemt_me_reconnect_success_total 20090
telemt_me_reader_eof_total 21238
telemt_me_idle_close_by_peer_total 21237
telemt_me_route_drop_no_conn_total 53806
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 158
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 21250
telemt_me_writer_restored_same_endpoint_total 20066
telemt_me_writer_removed_unexpected_minus_restored_total 1184
telemt_user_connections_total{user="hello"} 117872
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 837934284 (799.12 MB)
telemt_user_octets_to_client{user="hello"} 27491879192 (25.60 GB)
telemt_user_unique_ips_current{user="hello"} 30
```